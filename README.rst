
.. image:: avnu_logo.png

|

.. image:: https://travis-ci.org/AVnu/OpenAvnu.svg?branch=open-avb-next
   :target: https://travis-ci.org/AVnu/OpenAvnu

OpenAvnu
========

The OpenAvnu project is sponsored by the Avnu Alliance.
OpenAvnu 프로젝트는 Avnu Alliance가 지원합니다.

The intent is to provide components for building AVB/TSN systems. 
AVB / TSN 시스템을 구축하기위한 콤포너트(구성품)를 제공하는 것이 목적입니다.

The repository contains primarily network building block components - 
저장소는 주로 네트워크 구축 구성 요소를 포함합니다. - 

drivers, libraries, example applications  and daemon source code - 
드라이버들, 라이블러리들, 예제 프로그램들과 데몬 소스 코드 -

required to build an AVB/TSN system.
AVB/TSN 시스템을 구축하는데 필요합니다.

It is planned to eventually include the various packet encapsulation types,
protocol discovery daemons, libraries to convert media clocks to AVB clocks
and vice versa), and drivers.
궁극적으로 다양한 패킷 캡슐화 유형 프로토콜 검색 데몬, 
미디어 클럭 (AVB 클록 및 그 반대)으로 변환하는 라이브러리 및 드라이버를 
포함하는 계획을 가지고 있습니다.

This repository does not include all components required to build a full
production AVB/TSN system (e.g. a turnkey solution to stream stored or live audio
or video content). 
이 저장소에는 전체 프로덕션 AVB/TSN 시스템을 구축하는 데 필요한 모든 구성 요소 
(예: 저장된 오디오 또는 비디오 콘텐츠를 스트리밍하는 턴키 솔루션)가 포함되어 있지 않습니다.


Some simple example applications are provided which illustrate the flow - 
but a professional Audio/Video system requires a full media stack
- including audio and video inputs and outputs, media processing elements, and
various graphical user interfaces. 
흐름을 설명하는 몇 가지 간단한 예제 응용 프로그램이 제공되지만 
전문적인 오디오/비디오 시스템에는 오디오 및 비디오 입출력, 미디어 처리 요소 및 
다양한 그래픽 사용자 인터페이스를 포함한 전체 미디어 스택이 필요합니다.

Various companies provide such integrated solutions.
다양한 회사들이 이러한 솔루션들을 제공합니다.

For more information about AVB/TSN, see also the Avnu Alliance webpage at
www.avnu.org.
AVB/TSN에 대한 더 많은 정보는 Avnu 얼라이언스 웹페이지 (www.avnu.org)에서
볼 수 있습니다.


BACKGROUND
===========

Intel created the OpenAvnu repository to encourage collaborative source code
development for AVB/TSN technology enabling. 
인텔은 AVB/TSN 기술을 가능하게 하는 공동 소스 코드 개발을 장려하기 위해 
OpenAvnu 저장소를 만들었습니다.

By publishing the source code, our intent is to encourage standardization, 
stability and inter-operability between multiple vendors. 
소스 코드를 공개함으로써 여러 공급 업체 간의 표준화, 
안정성 및 상호 운용성을 장려하는 것이 우리의 목표입니다.

This repository - created by the Intel LAN Access Division -
is open for contributions from other vendors. 
Intel LAN Access Division에서 만든이 저장소는 다른 공급 업체의 공헌에 열려 있습니다.


LICENSING AND CONTRIBUTION GUIDELINES
======================================
To the extent possible, content is licensed under BSD licensing terms. 
가능한 한 컨텐츠는 BSD 라이센스 조항에 의거하여 라이센스가 부여됩니다.

Linux kernel mode components are provided under a GPLv2 license. 
Linux 커널 모드 구성 요소는 GPLv2 라이센스로 제공됩니다.

The specific license information is included in the various directories to eliminate confusion. 
특정 라이센스 정보는 혼동을 피하기 위해 여러 디렉토리에 포함됩니다.

We encourage you to review the ‘LICENSE’ file included in the head of the 
various subdirectories for details.
자세한 내용은 여러 하위 디렉토리 헤드에 포함된 '라이센스'파일을 검토하는 것이 좋습니다.

Third party submissions are welcomed. 
제 3 자 제출물을 환영합니다.

Our intent for third party content contributions is to enable derivative products 
with minimal licensing entanglements. 
제 3 자 콘텐츠 기여에 대한 당사의 의도는 최소한의 라이선스 얽힘을 사용하여 파생 제품을 사용 가능하게하는 것입니다.

Practically speaking, this means we would enforce (a) an 
original-source attestation for any contributed content, and (b) rejecting 
patches with GPL content into existing “BSD” licensed components. 
실질적으로 이것은 (a) 기여한 콘텐츠에 대한 원본 소스 증명을 시행하고 
(b) 기존 "BSD"라이선스 구성 요소에 GPL 콘텐츠가 포함 된 패치를 거부한다는 것을 의미합니다.

Third party copyrights can be included provided they do not narrow the licensing 
terms of an existing component.
기존 구성 요소의 라이센스 조항을 협의하지 않는 한 제 3 자의 저작권이 포함될 수 있습니다.

Prior to accepting a commit, Intel may perform scans using third-party tools to identify suspected hits of GPL code. 
커밋을 수락하기 전에 인텔은 타사 도구를 사용하여 스캔을 수행하여 의심되는 GPL 코드 히트를 식별 할 수 있습니다.

Intel may also perform vulnerability scans of patches in an attempt to find various coding errors such as memory 
leaks, buffer overflows and usage of uninitialized variables. 
인텔은 또한 메모리 누수, 버퍼 오버 플로우 및 초기화되지 않은 변수 사용과 같은 다양한 코딩 오류를 찾기 위해 패치의 취약점 검색을 수행 할 수 있습니다.

The submitter will be asked to correct any detected issues prior to a commit. 
제출자는 커미트 이전에 발견 된 문제를 수정하도록 요청받을 것입니다.

Owners of submitted third-party content are free to apply changes without supervision by Intel.
제출 된 타사 컨텐츠의 소유자는 Intel의 감독없이 변경 사항을 적용 할 수 있습니다.

The OpenAvnu project has a development mailing list. To subscribe, visit
https://lists.sourceforge.net/lists/listinfo/open-avb-devel to sign up.


WEBSITE
=======

A github based website for OpenAvnu can be found here.

+ http://avnu.github.io/OpenAvnu


GIT SUBMODULES
==============

After checking out the OpenAvnu git repository submodules should be configured by going::
OpenAvnu git 저장소를 체크 아웃 한 후 하위 모듈을 구성해야합니다.

    git submodule init
    git submodule update


CMAKE
=====

cmake is a cross-platform build system generator. cmake build files are
currently available to build mrpd in Windows and linux and CppUTest unit
tests for mrpd. The recommended usage for cmake is to create an out-of-tree
directory for cmake output of generated makefiles or MSVC project files.
cmake는 크로스 플랫폼 빌드 시스템 생성기입니다.  
cmake 빌드 파일은 현재 Windows 및 Linux에서 mrpd를 빌드하고 
mrpd에 대한 CppUTest 유닛 테스트를 빌드하는 데 사용할 수 있습니다.
cmake의 권장 사용법은 생성 된 makefile 또는 MSVC 프로젝트 파일의 
cmake 출력을 위한 트리가 아닌 디렉토리를 만드는 것입니다.

Starting from the OpenAvnu dir, one would go::

    mkdir tmp
    cd tmp
    cmake .. -G "Unix Makefiles"
    make

to build in OpenAvnu/tmp


RELATED OPEN SOURCE PROJECTS
============================

AVDECC
------
Jeff Koftinoff maintains a repository of AVDECC example open 
source code. AVDECC is a management layer, similar to SNMP MIB formats, 
which enables remote devices to detect, enumerate and configure AVB/TSN-related
devices based on their standardized management properties.
Jeff Koftinoff는 AVDECC 예제 오픈 소스 코드 저장소를 유지 관리합니다.  
AVDECC는 SNMP MIB 형식과 유사한 관리 계층으로, 원격 장치가 표준화 된 관리 속성을 기반으로 AVB / TSN 관련 장치를 검색, 열거 및 구성 할 수 있습니다.

+ https://github.com/jdkoftinoff/jdksavdecc-c

AudioScience has created a 1722.1 C++ controller library which builds on jdkadvecc-c.
AudioScience는 jdkadvecc-c를 기반으로하는 1722.1 C++ 컨트롤러 라이브러리를 만들었습니다.

+ https://github.com/audioscience/avdecc-lib


XMOS
----
XMOS is a semiconductor company providing a reference design for AVB/TSN
endpoints in pro audio and automotive. XMOS endpoint source code is open source 
and available on Github - https://github.com/xcore/sw_avb
XMOS는 프로 오디오 및 자동차 분야의 AVB/TSN 엔드 포인트에 대한 레퍼런스 디자인을 제공하는 반도체 회사입니다.
XMOS 엔드 포인트 소스 코드는 오픈 소스이며 Github에서 사용할 수 있습니다.

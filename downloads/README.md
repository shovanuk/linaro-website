---
layout: default-no-sub-nav
title: Downloads
permalink: /downloads/
---
## Downloads

Linaro code exists in many states and is found in many places. Working upstream means that the ultimate goal for most code is to be accepted and incorporated into something like the Linux kernel or GCC tool chain. The [Patches website](http://patches.linaro.org/) presents this work by team and by upstream project.

Before the code gets accepted upstream, Linaro maintains various development repositories and Linaro's groups make regular releases of various builds including Android, the LAVA test framework, key toolchains and builds for specific member products.

This page provides links to many of the more popular downloads produced by Linaro's [engineering teams](https://www.linaro.org/work/).

## Linaro Security Working Group downloads (including latest work on Meltdown/Spectre)

[Linaro security downloads](https://www.linaro.org/downloads/security/) are available from several of Linaro's engineering groups. The most recent work includes collaboration on Meltdown/Spectre fixes backported in to the 4.4, 4.9 and 4.14 kernels. There are also links to work from the Linaro Digital Home Group (LHG) and the latest OP-TEE work from the Security Working Group.

## Linaro Releases, Platforms and Snapshots

[Releases](http://releases.linaro.org/) is the main repository for Linaro code that has been tested and released. It is possible to navigate down through this site to find code if you know what you are looking for, but we recommend you use the links below for our most popular downloads.

[Platforms](https://platforms.linaro.org/documentation/Reference-Platform/Platforms/Enterprise/README.md/) is a new site that will host platform builds for specific end-to-end solutions. Currently, this site features the 16.12 release of the Enterprise Reference Platform, but we expect to post additional platform builds in the first half of 2017.

[Snapshots](http://snapshots.linaro.org/) code shows Linaro work in progress. Often created on a daily basis, these are literally snapshots of work in progress that are used for testing and development. The code on this site may not work and should only be used by experienced engineers who know exactly what they are doing.

## Linaro Member Builds

LMBs are full system builds of popular open-source products set up at the request of a Linaro Core/Club [Member](/members/) company.

{:.table.responsive-table}
|:---|:---|:---|:---|:---|
|ARM | <img src="/assets/images/thumbnails/content/aarch-64-logo.jpg" width="32px" height="auto" alt="AARCH 64 Logo" /> | Juno, Fixed Virtual Platforms (FVP), Versatile Express | [Platform release notes](http://community.arm.com/groups/arm-development-platforms)|
|Qualcomm | <img src="/assets/images/thumbnails/content/qualcomm-snapdragon.jpg" width="32px" height="auto" alt="Snapdragon Logo" /> | Download for Snapdragon 600 processor | [Snapdragon 600 Linux Platform](https://releases.linaro.org/debian/boards/snapdragon/latest/)|

***

## Linaro Stable Kernel (LSK)

The LSK is a version of kernel.org’s Long-Term Stable (LTS) release with new Linaro developed optimizations and ARM support integrated. There are two versions: a “Core” version for generic Linux and an “Android” version.


<ul>
<li>
<img src="{% asset_path 'icon-linux-logo-24x24.png' %}" alt="Linux Linaro">
<a href="https://git.linaro.org/kernel/linux-linaro-stable.git/">linux-linaro-stable (LSK) Git</a>,
<a href="https://wiki.linaro.org/LSK">additional information</a>
</li>
</ul>


***

## Linaro Confectionary Release (LCR)

R-LCR is a build of the Android Open Source Project (AOSP) from a stable release branch that includes platform support and other features. R-LCR includes the Android flavour of Linaro Stable Kernel (LSK) for all machine configurations.

- [R-LCR, Binaries](https://releases.linaro.org/android/reference-lcr/)

***

## LAVA

<div class="col-sm-9 no-padding" markdown="1">
The Linaro Automated Validation Architecture (LAVA) is a test and continuous integration framework that Linaro uses to validate its releases. The source is open so that members and others can create their own instantiations and run proprietary tests within this standard framework. [Click here for the latest downloads](https://releases.linaro.org/components/lava/latest/).
</div>
<div class="col-sm-3" markdown="1">
{% include image.html name="lava-logo_standard.png" class="pull-right" alt="Lava Logo Standard Image"%}
</div>
<div style="clear:both;"></div>
<hr>

## Linaro Networking

#### OpenDataPlane

<div class="col-sm-9 no-padding" markdown="1">
The [OpenDataPlane](http://www.opendataplane.org/) API has three implementations supported directly by LNG

- Functional reference model that runs on any linux implementation ([odp-linux-generic](https://git.linaro.org/lng/odp.git))
- Performance implementation build for x86  using the DPDK SDK. ([odp-dpdk](https://git.linaro.org/lng/odp-dpdk.git))
</div>
<div class="col-sm-3" markdown="1">
{% include image.html name="ODP-logo.png" class="pull-right" alt="ODP Logo"%}
</div>
<div style="clear:both;"></div>
<hr>

## Linaro Toolchain

Linaro provides monthly [GCC source archive](https://snapshots.linaro.org/components/toolchain/gcc-linaro/) snapshots of the current Linaro GCC release branch, as well as quarterly releases of pre-built Linaro [GNU cross-toolchain binary archives](https://releases.linaro.org/components/toolchain/binaries/).

The following tables provide direct access to the most common Linux and bare-metal ABI variants of the Linaro binary cross-toolchain quarterly releases.  Both x86_64 Linux and Mingw32 (MS Windows compatible) host binaries are provided:

#### Latest Linux Targeted Binary Toolchain Releases

<table class="table responsive-table">
<tbody>
<tr>
<td style="text-align:left"><strong>arm-linux-gnueabihf</strong></td>
<td style="text-align:left"><em>32-bit ARMv7 Cortex-A, hard-float, little-endian</em></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/">Release-Notes</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/arm-linux-gnueabihf/">Binaries</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/gcc-linaro/latest/">Source</a></td>
</tr>
<tr>
<td style="text-align:left"><strong>armv8l-linux-gnueabihf</strong></td>
<td style="text-align:left"><em>32-bit ARMv8 Cortex-A, hard-float, little-endian</em></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/">Release-Notes</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/armv8l-linux-gnueabihf/">Binaries</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/gcc-linaro/latest/">Source</a></td>
</tr>
<tr>
<td style="text-align:left"><strong>aarch64-linux-gnu</strong></td>
<td style="text-align:left"><em>64-bit ARMv8 Cortex-A, little-endian</em></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/">Release-Notes</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/binaries/latest/aarch64-linux-gnu/">Binaries</a></td>
<td style="text-align:left"><a href="https://releases.linaro.org/components/toolchain/gcc-linaro/latest/">Source</a></td>
</tr>
</tbody>
</table>


#### Latest Bare-Metal Targeted Binary Toolchain Releases

{:.table.responsive-table}
|:---|:---|:---|:---|:---|
|**arm-eabi**|_32-bit ARMv7 Cortex-A, soft-float, little-endian_|[Release-Notes](https://releases.linaro.org/components/toolchain/binaries/latest/)|[Binaries](https://releases.linaro.org/components/toolchain/binaries/latest/arm-eabi/)|[Source](https://releases.linaro.org/components/toolchain/gcc-linaro/latest/)|
|**aarch64-elf**|_64-bit ARMv8 Cortex-A, little-endian_|[Release-Notes](https://releases.linaro.org/components/toolchain/binaries/latest/)|[Binaries](https://releases.linaro.org/components/toolchain/binaries/latest/aarch64-elf/)|[Source](https://releases.linaro.org/components/toolchain/gcc-linaro/latest/)|

***

Interested in other target ABIs such as big-endian or soft-float little-endian? All toolchain target ABI and host variants can be seen [here](https://releases.linaro.org/components/toolchain/binaries/latest/). _Note: Not all ABI and host variants are supported to the same degree. See the [release-notes](https://releases.linaro.org/components/toolchain/binaries/latest/) for more information._

***

Interested in Cortex-R and Cortex-M bare-metal targeted toolchains for ARM embedded processors? We’re working with ARM to also supply a new release every year (with quarterly updates). Releases are maintained for two years. Get these from [Launchpad](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm)

***

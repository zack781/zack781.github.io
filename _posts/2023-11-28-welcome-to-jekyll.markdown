---
layout: post
title:  "Real-Time Audio Transport Plugin"
date:   2023-11-28 16:23:13 -0500
categories: jekyll update
---

[https://github.com/zack781/corelink-audio](https://github.com/zack781/corelink-audio)

This project aims to develope a high fidelity low latency audio transport plugin (VST,AU) using the Corelink network framework and JUCE audio framework.
Dependencies for Development:

- [Corelink c++](https://cpp-docs.hsrn.nyu.edu/)
- [oneTBB](https://github.com/oneapi-src/oneTBB)
- [JUCE](https://juce.com)

Header:

> ./corelink-client/cpp/include
> ./external-dependencies/cpp/asio-cpp/v1.24.0
> ./external-dependencies/cpp/rapidjson
> ./external-dependencies/cpp
> ./oneTBB/build/my_installed_onetbb/include/oneapi
> ./oneTBB/build/my_installed_onetbb/include
> ./oneTBB/build/my_installed_onetbb/include/tbb

Library:

> ./oneTBB/build//my_installed_onetbb/lib

Current source code can be found in ./testing_box
Existing support only for MAC. Window and Linux versions will be available in the near future.
More docs to come.

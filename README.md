# Nirvana

<img align="right" width="225px" src="https://user-images.githubusercontent.com/2191361/35839723-e9e5cdfa-0b2c-11e8-853a-8d3870f9e7ac.png">

[![Build Status](https://travis-ci.org/caicloud/nirvana.svg?branch=master)](https://travis-ci.org/caicloud/nirvana)
[![Coverage Status](https://coveralls.io/repos/github/caicloud/nirvana/badge.svg?branch=master)](https://coveralls.io/github/caicloud/nirvana?branch=master)
[![GoDoc](http://godoc.org/github.com/caicloud/nirvana?status.svg)](http://godoc.org/github.com/caicloud/nirvana)
[![Go Report Card](https://goreportcard.com/badge/github.com/caicloud/nirvana)](https://goreportcard.com/report/github.com/caicloud/nirvana)
[![OpenTracing Badge](https://img.shields.io/badge/OpenTracing-enabled-blue.svg)](http://opentracing.io)

Nirvana is a golang API framework designed for productivity and usability. It aims to be the building block for
all golang services in Caicloud. The high-level goals and features include:
Nirvana是一个为生产力和可用性而设计的golang API框架。它的目标是成为Caicloud中所有golang服务的基础。高级目标和特点包括:
* consistent API behavior, structure and layout across all golang projects
所有golang项目的API行为、结构和布局一致
* improve engineering productivity with openAPI and client generation, etc
使用openAPI和客户端生成等方法提高工程效率
* validation can be added by declaring validation method as part of API definition
可以通过声明验证方法作为API定义的一部分来添加验证
* out-of-box instrumentation support, e.g. metrics, profiling, tracing, etc
开箱即用的工具支持，例如度量、分析、跟踪等
* easy and standard configuration management, as well as standard cli interface
简单和标准的配置管理，以及标准cli接口
Nirvana is also extensible and performant, with the goal to support fast developmenet velocity.
Nirvana还具有可扩展性和性能，其目标是支持快速的开发速度。
## Getting Started

Nirvana provides two languages of documentations to help you to dig into this framework. But only chinese docs are fresh. If you can help to update these docs, we are very appreciate it. 

- [中文](https://caicloud.github.io/nirvana/zh-hans)
- [English (Expired)](https://caicloud.github.io/nirvana/en)

## Features

- API Framework based on Descriptors.
- Request Filter
- Middleware
- Validator
- Plugins
  - Metrics
  - Tracing
- API Doc Generation
- Client Generation

## Contributing

If you are intrested in this framework and want to contribute to it, you can get more deatils from [CONTRIBUTING.md](./CONTRIBUTING.md)

## Licensing

Nirvana is licensed under the Apache License, Version 2.0. See [LICENSE](./LICENSE) for the full license text.

 



<!---
 Licensed to the Apache Software Foundation (ASF) under one or more
 contributor license agreements.  See the NOTICE file distributed with
 this work for additional information regarding copyright ownership.
 The ASF licenses this file to You under the Apache License, Version 2.0
 (the "License"); you may not use this file except in compliance with
 the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->


![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/apache/maven.svg?label=License)


# Maven Release Plugin (Fork)

**This is a fork of the [Apache Maven Release Plugin](https://maven.apache.org/maven-release/maven-release-plugin/) project.**

This fork adds experimental/limited support for operations with Git submodules.
Specifically, when `commitByProject` is enabled, the plugin will not attempt to make separate commits to the super-module's SCM. Instead, it will make a separate commit and push to the repository specified in each module's SCM section.
**Note:** All Maven sub-projects must either be in Git submodules or none can be; mixing is not supported.

## Original Project

See the [upstream repository](https://github.com/apache/maven-release) for documentation, issues, and full feature set.

_This project is not affiliated with or endorsed by the Apache Software Foundation._
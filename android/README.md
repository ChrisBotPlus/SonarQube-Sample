# Android Architecture Blueprints
<p align="center">
<img src="https://github.com/googlesamples/android-architecture/wiki/images/aab-logov2.png" alt="Illustration by Virginia Poltrack"/>
</p>

Android Architecture Blueprints is a kotlin project to showcase different architectural approaches to developing Android apps. 
The original sample can be found here: <a>https://github.com/android/architecture-samples</a> 

# Customisation 
1. Remove some invalid unit test classes
2. Modify build.gradle in order to add Jacoco dependencies
3. Modify app/build.gradle to apply jacoco.gradle
4. New file jacoco.gradle to define test coverage behavior
5. New file sonar-project.properties for SonarQube scanning params

# Procedures

## Unit Test
`./gradlew testDebugUnitTest` 

## Generate Test Coverage Report
`./gradlew createDebugCoverageReport` 

## Run Sonar Scanner
`sonar-scanner` 


### License


```
Copyright 2022 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements. See the NOTICE file distributed with this work for
additional information regarding copyright ownership. The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
```

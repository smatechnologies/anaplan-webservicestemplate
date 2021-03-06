# Anaplan WebServices template
This template allows you to make calls to the Anaplan API to start/monitor an Anaplan Export.

# Prerequisites
* OpCon 18.3+
* WebServices Connector 20.1+ (recommended)
* Anaplan API v2.0

# Instructions
Import the template to a new Web Services connector job in OpCon.  The template contains 5 steps:  

Variables -
 * @anaplantoken - The authorization token used for communicating with the Anaplan API (store in an encrypted global property)

"Step 1/2/3" Retrieves information (workspace, model, export process) used to find the correct Export process to execute.

"Step 4" Executes the Export process and retreives the unique id.

"Step 5" Monitors the Export process containing the id from Step 4 until completion. 

# Disclaimer
No Support and No Warranty are provided by SMA Technologies for this project and related material. The use of this project's files is on your own risk.

SMA Technologies assumes no liability for damage caused by the usage of any of the files offered here via this Github repository.

# License
Copyright 2019 SMA Technologies

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Contributing
We love contributions, please read our [Contribution Guide](CONTRIBUTING.md) to get started!

# Code of Conduct
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
SMA Technologies has adopted the [Contributor Covenant](CODE_OF_CONDUCT.md) as its Code of Conduct, and we expect project participants to adhere to it. Please read the [full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

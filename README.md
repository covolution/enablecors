# Enables Cors support for an Alfresco repository#
Add this jar to the `modules/platform` directory and you should be good to go.

Tested on Alfresco 5.1.

## Implementation
The jar just contains a `webfragment.xml` that configures the `com.thetransactioncompany.cors.CORSFilter` available in the classpath.

## Rest Api Explorer
I recommend checking out [api-explorer.alfresco.com](http://api-explorer.alfresco.com) and the source is [here](https://github.com/Alfresco/rest-api-explorer).

The Api Explorer makes use of [Open Api](https://openapis.org/specification) (aka Swagger) definitions. If you would like these definitions within the Alfresco.war (perhaps to support custom tooling) then checkout the `withdev` branch of this project.

### License
Copyright (C) 2016 Alfresco Software Limited

This file is part of an unsupported extension to Alfresco.

Alfresco Software Limited licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.

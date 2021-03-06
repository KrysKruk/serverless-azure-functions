# [2.0.0](https://github.com/serverless/serverless-azure-functions/compare/v1.0.0...v2.0.0)

### Features

* Support for .NET Core Function Apps ([#449](https://github.com/serverless/serverless-azure-functions/issues/449)) ([7282ecc](https://github.com/serverless/serverless-azure-functions/commit/7282ecc))
* Invoke APIM endpoint ([#442](https://github.com/serverless/serverless-azure-functions/issues/442)) ([8b61c38](https://github.com/serverless/serverless-azure-functions/commit/8b61c38))
* Remove --force command ([#441](https://github.com/serverless/serverless-azure-functions/issues/441)) ([c0cda45](https://github.com/serverless/serverless-azure-functions/commit/c0cda45))
* Info plugin and deploy dry-run ([#405](https://github.com/serverless/serverless-azure-functions/issues/405)) ([1badd77](https://github.com/serverless/serverless-azure-functions/commit/1badd77))
* Eliminate need for 'x-azure-settings' config ([#404](https://github.com/serverless/serverless-azure-functions/issues/404)) ([cbd9173](https://github.com/serverless/serverless-azure-functions/commit/cbd9173))
* Use cross-spawn instead of adding .cmd ([#434](https://github.com/serverless/serverless-azure-functions/issues/434)) ([1054601](https://github.com/serverless/serverless-azure-functions/commit/1054601))
* Linux & Python Runtime Support ([#420](https://github.com/serverless/serverless-azure-functions/issues/420)) ([2180a9a](https://github.com/serverless/serverless-azure-functions/commit/2180a9a)), closes [#429](https://github.com/serverless/serverless-azure-functions/issues/429)
* Logging Service to allow configurable verbosity ([#401](https://github.com/serverless/serverless-azure-functions/issues/401)) ([e0339ed](https://github.com/serverless/serverless-azure-functions/commit/e0339ed))
* Adds support for APIM check-header policy ([#394](https://github.com/serverless/serverless-azure-functions/issues/394)) ([7e996fe](https://github.com/serverless/serverless-azure-functions/commit/7e996fe))
* Prompt user for confirmation to remove resource group ([#383](https://github.com/serverless/serverless-azure-functions/issues/383)) ([f2e96a1](https://github.com/serverless/serverless-azure-functions/commit/f2e96a1))
* Cache provider config on initialization ([#385](https://github.com/serverless/serverless-azure-functions/issues/385)) ([7b57c82](https://github.com/serverless/serverless-azure-functions/commit/7b57c82))
* Fetch bindings.json from official Azure Functions repo ([#364](https://github.com/serverless/serverless-azure-functions/issues/364)) ([4e30115](https://github.com/serverless/serverless-azure-functions/commit/4e30115))
* Updated scaling support in premium app service plan ([#386](https://github.com/serverless/serverless-azure-functions/issues/386)) ([1c3923c](https://github.com/serverless/serverless-azure-functions/commit/1c3923c))
* Refactored APIM policies into reusable builder component ([#387](https://github.com/serverless/serverless-azure-functions/issues/387)) ([0e7c23c](https://github.com/serverless/serverless-azure-functions/commit/0e7c23c))
* Service resource group tagging ([#358](https://github.com/serverless/serverless-azure-functions/issues/358)) ([879e56e](https://github.com/serverless/serverless-azure-functions/commit/879e56e))
* ConfigService for centralizing configuration and simplifying BaseService ([#338](https://github.com/serverless/serverless-azure-functions/issues/338)) ([f179152](https://github.com/serverless/serverless-azure-functions/commit/f179152))
* Refactor runtime configuration to allow for non-node runtimes ([#348](https://github.com/serverless/serverless-azure-functions/issues/348)) ([ccec102](https://github.com/serverless/serverless-azure-functions/commit/ccec102))
* Refactor runtime configuration to allow for non-node runtimes ([#348](https://github.com/serverless/serverless-azure-functions/issues/348)) ([e943b57](https://github.com/serverless/serverless-azure-functions/commit/e943b57))
* ConfigService for centralizing configuration and simplifying BaseService ([#338](https://github.com/serverless/serverless-azure-functions/issues/338)) ([36578d1](https://github.com/serverless/serverless-azure-functions/commit/36578d1))

### Bug Fixes

* Print error message for invoke command ([#458](https://github.com/serverless/serverless-azure-functions/issues/458)) ([947a305](https://github.com/serverless/serverless-azure-functions/commit/947a305))
* Log functions in external deployment ([#456](https://github.com/serverless/serverless-azure-functions/issues/456)) ([379ebdb](https://github.com/serverless/serverless-azure-functions/commit/379ebdb))
* adding cosmosDBIn as an accepted trigger ([#453](https://github.com/serverless/serverless-azure-functions/issues/453)) ([237d432](https://github.com/serverless/serverless-azure-functions/commit/237d432))
* Specifying storage account name ([#426](https://github.com/serverless/serverless-azure-functions/issues/426)) ([5e5d80e](https://github.com/serverless/serverless-azure-functions/commit/5e5d80e))
* Add functionAppReserved back into ARM template ([#448](https://github.com/serverless/serverless-azure-functions/issues/448)) ([78f2184](https://github.com/serverless/serverless-azure-functions/commit/78f2184))
* Move reserved prop to App Service Plan ([#443](https://github.com/serverless/serverless-azure-functions/issues/443)) ([68ac06c](https://github.com/serverless/serverless-azure-functions/commit/68ac06c))
* Remove -v shortcut for --verbose, conflicts with --version ([#435](https://github.com/serverless/serverless-azure-functions/issues/435)) ([c0b1666](https://github.com/serverless/serverless-azure-functions/commit/c0b1666))
* Update version of Azure Functions Core tools ([#433](https://github.com/serverless/serverless-azure-functions/issues/433)) ([c3ca97b](https://github.com/serverless/serverless-azure-functions/commit/c3ca97b))
* Don't try to clean up non-existent directories ([#402](https://github.com/serverless/serverless-azure-functions/issues/402)) ([71b530e](https://github.com/serverless/serverless-azure-functions/commit/71b530e))
* Hot fix for undefined params ([#411](https://github.com/serverless/serverless-azure-functions/issues/411)) ([871fb07](https://github.com/serverless/serverless-azure-functions/commit/871fb07))
* Fix typing errors in ARM params and add interfaces ([#347](https://github.com/serverless/serverless-azure-functions/issues/347)) ([de18b35](https://github.com/serverless/serverless-azure-functions/commit/de18b35))
* Sort deployments in descending order and fix APIM arm template ([#354](https://github.com/serverless/serverless-azure-functions/issues/354)) ([8ad45be](https://github.com/serverless/serverless-azure-functions/commit/8ad45be))
* Sync triggers on external package deployment ([#339](https://github.com/serverless/serverless-azure-functions/issues/339)) ([e899129](https://github.com/serverless/serverless-azure-functions/commit/e899129))
* Update GitHub Issue and PR templates ([#353](https://github.com/serverless/serverless-azure-functions/issues/353)) ([6ae5b6c](https://github.com/serverless/serverless-azure-functions/commit/6ae5b6c))
* Update to support CosmosDB bindings ([#350](https://github.com/serverless/serverless-azure-functions/issues/350)) ([c4c8bfa](https://github.com/serverless/serverless-azure-functions/commit/c4c8bfa))
* Sort deployments in descending order and fix APIM arm template ([#354](https://github.com/serverless/serverless-azure-functions/issues/354)) ([865cfd0](https://github.com/serverless/serverless-azure-functions/commit/865cfd0))
* Update GitHub Issue and PR templates ([#353](https://github.com/serverless/serverless-azure-functions/issues/353)) ([847a74b](https://github.com/serverless/serverless-azure-functions/commit/847a74b))
* Update to support CosmosDB bindings ([#350](https://github.com/serverless/serverless-azure-functions/issues/350)) ([865fd46](https://github.com/serverless/serverless-azure-functions/commit/865fd46))
* Fix typing errors in ARM params and add interfaces ([#347](https://github.com/serverless/serverless-azure-functions/issues/347)) ([3e76d4c](https://github.com/serverless/serverless-azure-functions/commit/3e76d4c))
* Sync triggers on external package deployment ([#339](https://github.com/serverless/serverless-azure-functions/issues/339)) ([48b914f](https://github.com/serverless/serverless-azure-functions/commit/48b914f))

# [1.0.0](https://github.com/serverless/serverless-azure-functions/compare/v0.7.0...v1.0.0)

### Features

* Add `hooks` type to base plugin, document plugin options for CLI help ([#245](https://github.com/serverless/serverless-azure-functions/issues/245)) ([317db2d](https://github.com/serverless/serverless-azure-functions/commit/317db2d)), closes [AB#802](https://github.com/AB/issues/802) [AB#795](https://github.com/AB/issues/795)
* Add azure-functions-core-tools to dependencies ([#261](https://github.com/serverless/serverless-azure-functions/issues/261)) ([860b60d](https://github.com/serverless/serverless-azure-functions/commit/860b60d))
* Add options to base plugin class ([#198](https://github.com/serverless/serverless-azure-functions/issues/198)) ([71bbd5d](https://github.com/serverless/serverless-azure-functions/commit/71bbd5d))
* add support for specifying resourceGroup in both cli and yaml ([#189](https://github.com/serverless/serverless-azure-functions/issues/189)) ([956ab9c](https://github.com/serverless/serverless-azure-functions/commit/956ab9c))
* Added Azure Naming Service ([#221](https://github.com/serverless/serverless-azure-functions/issues/221)) ([6886fb0](https://github.com/serverless/serverless-azure-functions/commit/6886fb0)), closes [AB#597](https://github.com/AB/issues/597)
* Added feature to specify Azure subcription ID in CLI before deployment ([#203](https://github.com/serverless/serverless-azure-functions/issues/203)) ([9528407](https://github.com/serverless/serverless-azure-functions/commit/9528407))
* Added npm script to generate service principal ([#196](https://github.com/serverless/serverless-azure-functions/issues/196)) ([0fd1d9f](https://github.com/serverless/serverless-azure-functions/commit/0fd1d9f))
* Adds webpack support for azure plugin ([#164](https://github.com/serverless/serverless-azure-functions/issues/164)) ([6b8ac24](https://github.com/serverless/serverless-azure-functions/commit/6b8ac24))
* APIM example doc ([#225](https://github.com/serverless/serverless-azure-functions/issues/225)) ([d2d9a2f](https://github.com/serverless/serverless-azure-functions/commit/d2d9a2f))
* APIM feature updates ([#312](https://github.com/serverless/serverless-azure-functions/issues/312)) ([69efbf7](https://github.com/serverless/serverless-azure-functions/commit/69efbf7))
* Azure API management ([#157](https://github.com/serverless/serverless-azure-functions/issues/157)) ([0f54201](https://github.com/serverless/serverless-azure-functions/commit/0f54201))
* Azure Blob Storage service ([#177](https://github.com/serverless/serverless-azure-functions/issues/177)) ([0f6242d](https://github.com/serverless/serverless-azure-functions/commit/0f6242d)), closes [AB#361](https://github.com/AB/issues/361)
* Azure Functions Offline plugin ([#159](https://github.com/serverless/serverless-azure-functions/issues/159)) ([29cd8be](https://github.com/serverless/serverless-azure-functions/commit/29cd8be)), closes [AB#257](https://github.com/AB/issues/257)
* Azure Key Vault YAML setup support ([#285](https://github.com/serverless/serverless-azure-functions/issues/285)) ([ee76d3f](https://github.com/serverless/serverless-azure-functions/commit/ee76d3f))
* Azure Packaging updates ([#163](https://github.com/serverless/serverless-azure-functions/issues/163)) ([18ca8c6](https://github.com/serverless/serverless-azure-functions/commit/18ca8c6)), closes [ABA#82](https://github.com/ABA/issues/82)
* Azure Pipelines CI pipeline & script ([#223](https://github.com/serverless/serverless-azure-functions/issues/223)) ([905052d](https://github.com/serverless/serverless-azure-functions/commit/905052d)), closes [AB#588](https://github.com/AB/issues/588)
* Azure region & stage defaults ([#172](https://github.com/serverless/serverless-azure-functions/issues/172)) ([412eec8](https://github.com/serverless/serverless-azure-functions/commit/412eec8))
* Cache interactive login credentials ([#222](https://github.com/serverless/serverless-azure-functions/issues/222)) ([ffedfe0](https://github.com/serverless/serverless-azure-functions/commit/ffedfe0))
* Converted project to typescript ([#139](https://github.com/serverless/serverless-azure-functions/issues/139)) ([ed1c9d1](https://github.com/serverless/serverless-azure-functions/commit/ed1c9d1)), closes [AB#18671](https://github.com/AB/issues/18671)
* Deploy APIM CORS Policy ([#166](https://github.com/serverless/serverless-azure-functions/issues/166)) ([3138108](https://github.com/serverless/serverless-azure-functions/commit/3138108)), closes [ABA#207](https://github.com/ABA/issues/207)
* Deploy function app code from blob storage URL ([#231](https://github.com/serverless/serverless-azure-functions/issues/231)) ([6ce0536](https://github.com/serverless/serverless-azure-functions/commit/6ce0536)), closes [AB#488](https://github.com/AB/issues/488)
* Deploy pre-existing package with `-p` CLI option ([#205](https://github.com/serverless/serverless-azure-functions/issues/205)) ([15d2980](https://github.com/serverless/serverless-azure-functions/commit/15d2980)), closes [AB#500](https://github.com/AB/issues/500)
* Dynamically generate ARM templates ([#174](https://github.com/serverless/serverless-azure-functions/issues/174)) ([f27b87e](https://github.com/serverless/serverless-azure-functions/commit/f27b87e))
* Enabled jest configuration to work in VS code ([#146](https://github.com/serverless/serverless-azure-functions/issues/146)) ([d318a4f](https://github.com/serverless/serverless-azure-functions/commit/d318a4f))
* Func plugin to add/remove functions within function app ([#151](https://github.com/serverless/serverless-azure-functions/issues/151)) ([8e44411](https://github.com/serverless/serverless-azure-functions/commit/8e44411))
* Handle SIGINT and cleanup offline files unless specified to skip ([#233](https://github.com/serverless/serverless-azure-functions/issues/233)) ([d6c8e9e](https://github.com/serverless/serverless-azure-functions/commit/d6c8e9e))
* Invoke function locally ([#264](https://github.com/serverless/serverless-azure-functions/issues/264)) ([14affa2](https://github.com/serverless/serverless-azure-functions/commit/14affa2)), closes [#260](https://github.com/serverless/serverless-azure-functions/issues/260)
* List deployments for rollback when no timestamp given ([#208](https://github.com/serverless/serverless-azure-functions/issues/208)) ([f5268b4](https://github.com/serverless/serverless-azure-functions/commit/f5268b4)), closes [AB#493](https://github.com/AB/issues/493)
* List deployments sub-command for deploy plugin ([#176](https://github.com/serverless/serverless-azure-functions/issues/176)) ([d753d56](https://github.com/serverless/serverless-azure-functions/commit/d753d56)), closes [AB#352](https://github.com/AB/issues/352)
* Mock of Serverless object for unit tests ([#144](https://github.com/serverless/serverless-azure-functions/issues/144)) ([bb6b08f](https://github.com/serverless/serverless-azure-functions/commit/bb6b08f)), closes [AB#18712](https://github.com/AB/issues/18712)
* More detailed error message upon ARM deployment failure ([#306](https://github.com/serverless/serverless-azure-functions/issues/306)) ([4c7c5de](https://github.com/serverless/serverless-azure-functions/commit/4c7c5de))
* Path from x-azure-settings is included in function.json ([#212](https://github.com/serverless/serverless-azure-functions/issues/212)) ([55620ee](https://github.com/serverless/serverless-azure-functions/commit/55620ee)), closes [AB#552](https://github.com/AB/issues/552)
* Release and pre-release pipelines with publish script ([#224](https://github.com/serverless/serverless-azure-functions/issues/224)) ([b3a0648](https://github.com/serverless/serverless-azure-functions/commit/b3a0648)), closes [AB#588](https://github.com/AB/issues/588)
* Rollback Plugin ([#191](https://github.com/serverless/serverless-azure-functions/issues/191)) ([7fe23e2](https://github.com/serverless/serverless-azure-functions/commit/7fe23e2)), closes [AB#317](https://github.com/AB/issues/317)
* Set GET as default HTTP method for APIM inferred configuration ([#328](https://github.com/serverless/serverless-azure-functions/issues/328)) ([9fc8023](https://github.com/serverless/serverless-azure-functions/commit/9fc8023))
* Spawn offline process with `sls offline` command ([#214](https://github.com/serverless/serverless-azure-functions/issues/214)) ([92a8abb](https://github.com/serverless/serverless-azure-functions/commit/92a8abb))
* Specify Node.js runtime version in serverless.yml ([#257](https://github.com/serverless/serverless-azure-functions/issues/257)) ([b940048](https://github.com/serverless/serverless-azure-functions/commit/b940048)), closes [AB#704](https://github.com/AB/issues/704)
* specify subscription ID in serverless yaml ([259175b](https://github.com/serverless/serverless-azure-functions/commit/259175b))
* Updates to deployment process to enable rollback (Part 2) ([#185](https://github.com/serverless/serverless-azure-functions/issues/185)) ([51c95a4](https://github.com/serverless/serverless-azure-functions/commit/51c95a4)), closes [AB#388](https://github.com/AB/issues/388) [AB#358](https://github.com/AB/issues/358) [AB#414](https://github.com/AB/issues/414) [AB#415](https://github.com/AB/issues/415)
* Use development storage for offline build ([#296](https://github.com/serverless/serverless-azure-functions/issues/296)) ([6e34a84](https://github.com/serverless/serverless-azure-functions/commit/6e34a84))
* Wait longer and only print one retry message for deploying a function app ([#283](https://github.com/serverless/serverless-azure-functions/issues/283)) ([1ffbd69](https://github.com/serverless/serverless-azure-functions/commit/1ffbd69))

### Bug Fixes

* Add backwards compatibility for location/region keys in config ([#305](https://github.com/serverless/serverless-azure-functions/issues/305)) ([b5a74d8](https://github.com/serverless/serverless-azure-functions/commit/b5a74d8)), closes [#280](https://github.com/serverless/serverless-azure-functions/issues/280)
* add resource group name hash to resource names ([#310](https://github.com/serverless/serverless-azure-functions/issues/310)) ([a475df3](https://github.com/serverless/serverless-azure-functions/commit/a475df3)), closes [#311](https://github.com/serverless/serverless-azure-functions/issues/311)
* Add retry support when listing deployed functions ([#215](https://github.com/serverless/serverless-azure-functions/issues/215)) ([ea71d09](https://github.com/serverless/serverless-azure-functions/commit/ea71d09))
* Add sequence diagram png files ([#184](https://github.com/serverless/serverless-azure-functions/issues/184)) ([292fad1](https://github.com/serverless/serverless-azure-functions/commit/292fad1))
* Added access modifiers to shared services ([2b3aa95](https://github.com/serverless/serverless-azure-functions/commit/2b3aa95))
* api uses shortened region names ([#211](https://github.com/serverless/serverless-azure-functions/issues/211)) ([3691a3f](https://github.com/serverless/serverless-azure-functions/commit/3691a3f))
* Append 6-char resource group hash to storage account name ([#256](https://github.com/serverless/serverless-azure-functions/issues/256)) ([4af8521](https://github.com/serverless/serverless-azure-functions/commit/4af8521)), closes [AB#846](https://github.com/AB/issues/846)
* Check for valid entries in token cache remove and find ([#244](https://github.com/serverless/serverless-azure-functions/issues/244)) ([326a037](https://github.com/serverless/serverless-azure-functions/commit/326a037))
* Clean up .serverless folder before packaging new artifact ([#275](https://github.com/serverless/serverless-azure-functions/issues/275)) ([f5d50dd](https://github.com/serverless/serverless-azure-functions/commit/f5d50dd))
* Clean up downloaded artifact after rollback ([#289](https://github.com/serverless/serverless-azure-functions/issues/289)) ([357a609](https://github.com/serverless/serverless-azure-functions/commit/357a609)), closes [#287](https://github.com/serverless/serverless-azure-functions/issues/287)
* Combine rollback log statement into one string ([#290](https://github.com/serverless/serverless-azure-functions/issues/290)) ([4c4fa78](https://github.com/serverless/serverless-azure-functions/commit/4c4fa78))
* Crash deployment if function app zip file doesn't exist ([#242](https://github.com/serverless/serverless-azure-functions/issues/242)) ([f5cbe45](https://github.com/serverless/serverless-azure-functions/commit/f5cbe45))
* Create default .azure directory if not present ([#318](https://github.com/serverless/serverless-azure-functions/issues/318)) ([21ac3eb](https://github.com/serverless/serverless-azure-functions/commit/21ac3eb))
* Default operation names no longer cause collisions ([#332](https://github.com/serverless/serverless-azure-functions/issues/332)) ([09863e7](https://github.com/serverless/serverless-azure-functions/commit/09863e7))
* Don't remove local.settings.json in offline cleanup ([#267](https://github.com/serverless/serverless-azure-functions/issues/267)) ([016b27c](https://github.com/serverless/serverless-azure-functions/commit/016b27c))
* Don't require login during packaging. ([fb9db98](https://github.com/serverless/serverless-azure-functions/commit/fb9db98)), closes [AB#801](https://github.com/AB/issues/801)
* Don't skip deploy if previous equivalent deployment failed ([#247](https://github.com/serverless/serverless-azure-functions/issues/247)) ([eb79bcc](https://github.com/serverless/serverless-azure-functions/commit/eb79bcc)), closes [AB#852](https://github.com/AB/issues/852)
* Don't throw error if subscription ID already specified ([#295](https://github.com/serverless/serverless-azure-functions/issues/295)) ([a944b57](https://github.com/serverless/serverless-azure-functions/commit/a944b57))
* Ensures the correct SCM domain is found for uploading zip package ([#178](https://github.com/serverless/serverless-azure-functions/issues/178)) ([7cdb55c](https://github.com/serverless/serverless-azure-functions/commit/7cdb55c))
* Exclude ARM params with null values ([#325](https://github.com/serverless/serverless-azure-functions/issues/325)) ([8c01f62](https://github.com/serverless/serverless-azure-functions/commit/8c01f62))
* exclude test files ([#246](https://github.com/serverless/serverless-azure-functions/issues/246)) ([14109da](https://github.com/serverless/serverless-azure-functions/commit/14109da)), closes [AB#804](https://github.com/AB/issues/804)
* Exit process when error logging into Azure ([#192](https://github.com/serverless/serverless-azure-functions/issues/192)) ([1f9e473](https://github.com/serverless/serverless-azure-functions/commit/1f9e473))
* Fix appServicePlan name and functionApp name ([#293](https://github.com/serverless/serverless-azure-functions/issues/293)) ([f7684f4](https://github.com/serverless/serverless-azure-functions/commit/f7684f4)), closes [#292](https://github.com/serverless/serverless-azure-functions/issues/292)
* Fix bug with invalid token file for interactive login ([#243](https://github.com/serverless/serverless-azure-functions/issues/243)) ([c7f080d](https://github.com/serverless/serverless-azure-functions/commit/c7f080d)), closes [AB#838](https://github.com/AB/issues/838)
* Fix compiler errors and remove logs plugin ([#286](https://github.com/serverless/serverless-azure-functions/issues/286)) ([601e78d](https://github.com/serverless/serverless-azure-functions/commit/601e78d))
* Fix failing invoke with data path ([#321](https://github.com/serverless/serverless-azure-functions/issues/321)) ([bad7146](https://github.com/serverless/serverless-azure-functions/commit/bad7146)), closes [#320](https://github.com/serverless/serverless-azure-functions/issues/320)
* Fix misnamed variable in test ([#179](https://github.com/serverless/serverless-azure-functions/issues/179)) ([5afe8dc](https://github.com/serverless/serverless-azure-functions/commit/5afe8dc))
* Fix regression of skipping identical ARM deployment ([#314](https://github.com/serverless/serverless-azure-functions/issues/314)) ([02d1024](https://github.com/serverless/serverless-azure-functions/commit/02d1024))
* Inject current environment variables to spawn process ([#218](https://github.com/serverless/serverless-azure-functions/issues/218)) ([2f3b116](https://github.com/serverless/serverless-azure-functions/commit/2f3b116))
* Invoke offline without requiring global install ([#322](https://github.com/serverless/serverless-azure-functions/issues/322)) ([1a77ff5](https://github.com/serverless/serverless-azure-functions/commit/1a77ff5))
* issue fixed to generate the correct function.json for event hub and service bus queue and topic triggers ([#228](https://github.com/serverless/serverless-azure-functions/issues/228)) ([79a2576](https://github.com/serverless/serverless-azure-functions/commit/79a2576))
* Let Serverless Framework handle thrown error ([#238](https://github.com/serverless/serverless-azure-functions/issues/238)) ([740d4b0](https://github.com/serverless/serverless-azure-functions/commit/740d4b0))
* Log correct function app name in deployment ([#304](https://github.com/serverless/serverless-azure-functions/issues/304)) ([fa71648](https://github.com/serverless/serverless-azure-functions/commit/fa71648))
* Move InvokeService variable initialization outside of the constructor header ([#270](https://github.com/serverless/serverless-azure-functions/issues/270)) ([ed5b0f1](https://github.com/serverless/serverless-azure-functions/commit/ed5b0f1))
* Move service initialization outside of plugins ([#301](https://github.com/serverless/serverless-azure-functions/issues/301)) ([f483b9a](https://github.com/serverless/serverless-azure-functions/commit/f483b9a))
* Register missing dependency ([#237](https://github.com/serverless/serverless-azure-functions/issues/237)) ([865f92a](https://github.com/serverless/serverless-azure-functions/commit/865f92a))
* Remove await statement from Promise.all ([#194](https://github.com/serverless/serverless-azure-functions/issues/194)) ([933ff2e](https://github.com/serverless/serverless-azure-functions/commit/933ff2e))
* Remove dead, outdated AzureProvider code ([#276](https://github.com/serverless/serverless-azure-functions/issues/276)) ([54d1296](https://github.com/serverless/serverless-azure-functions/commit/54d1296))
* Removed service name from storage account name generator ([#232](https://github.com/serverless/serverless-azure-functions/issues/232)) ([d1fcfc9](https://github.com/serverless/serverless-azure-functions/commit/d1fcfc9))
* Resolves issues running plugin  ([#141](https://github.com/serverless/serverless-azure-functions/issues/141)) ([4fd9642](https://github.com/serverless/serverless-azure-functions/commit/4fd9642))
* Run install before generating changelog ([#335](https://github.com/serverless/serverless-azure-functions/issues/335)) ([f8c0c42](https://github.com/serverless/serverless-azure-functions/commit/f8c0c42))
* set up npm auth ([#272](https://github.com/serverless/serverless-azure-functions/issues/272)) ([be0ef95](https://github.com/serverless/serverless-azure-functions/commit/be0ef95))
* Throw error if user tries to specify function for deployment ([#262](https://github.com/serverless/serverless-azure-functions/issues/262)) ([8eee996](https://github.com/serverless/serverless-azure-functions/commit/8eee996)), closes [#258](https://github.com/serverless/serverless-azure-functions/issues/258)
* Throw error if user tries to specify package.individually ([#263](https://github.com/serverless/serverless-azure-functions/issues/263)) ([df59b98](https://github.com/serverless/serverless-azure-functions/commit/df59b98)), closes [#254](https://github.com/serverless/serverless-azure-functions/issues/254)
* Throw original error if no previous deployments ([#324](https://github.com/serverless/serverless-azure-functions/issues/324)) ([d80cfef](https://github.com/serverless/serverless-azure-functions/commit/d80cfef))
* Update generate changelog script to reference local node module ([#334](https://github.com/serverless/serverless-azure-functions/issues/334)) ([6b0a3ee](https://github.com/serverless/serverless-azure-functions/commit/6b0a3ee))
* Update storage account naming convention ([#190](https://github.com/serverless/serverless-azure-functions/issues/190)) ([30d4daf](https://github.com/serverless/serverless-azure-functions/commit/30d4daf)), closes [AB#420](https://github.com/AB/issues/420)
* Updates default http output binding ([#308](https://github.com/serverless/serverless-azure-functions/issues/308)) ([e7473a1](https://github.com/serverless/serverless-azure-functions/commit/e7473a1)), closes [Azure/azure-functions-nodejs-worker#228](https://github.com/Azure/azure-functions-nodejs-worker/issues/228)
* Use stage, region, resourceGroup and prefix from CLI options ([#284](https://github.com/serverless/serverless-azure-functions/issues/284)) ([30f5d1b](https://github.com/serverless/serverless-azure-functions/commit/30f5d1b)), closes [#280](https://github.com/serverless/serverless-azure-functions/issues/280) [#282](https://github.com/serverless/serverless-azure-functions/issues/282) [#281](https://github.com/serverless/serverless-azure-functions/issues/281)

### Performance Improvements

* Short-circuit deployment if ARM template hasn't changed ([#239](https://github.com/serverless/serverless-azure-functions/issues/239)) ([60a75b2](https://github.com/serverless/serverless-azure-functions/commit/60a75b2)), closes [AB#789](https://github.com/AB/issues/789)
* Skip upload to function app if configured to run from blob ([#241](https://github.com/serverless/serverless-azure-functions/issues/241)) ([f734f08](https://github.com/serverless/serverless-azure-functions/commit/f734f08))

# [0.7.0](https://github.com/serverless/serverless-azure-functions/compare/v0.6.0...v0.7.0)

# [0.6.0](https://github.com/serverless/serverless-azure-functions/compare/v0.5.0...v0.6.0)

# [0.5.0](https://github.com/serverless/serverless-azure-functions/compare/v0.4.0...v0.5.0)

# [0.4.0](https://github.com/serverless/serverless-azure-functions/compare/v0.3.0...v0.4.0)

# [0.3.0](https://github.com/serverless/serverless-azure-functions/compare/v0.2.0...v0.3.0)

# [0.2.0](https://github.com/serverless/serverless-azure-functions/releases/tag/v0.2.0)


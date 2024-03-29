# Change Log

## [5.1.0](https://github.com/chef/chef-zero/tree/5.1.0) (2016-09-07)
[Full Changelog](https://github.com/chef/chef-zero/compare/v5.0.0...5.1.0)

**Implemented enhancements:**

- store ACEs by client/user [\#240](https://github.com/chef/chef-zero/pull/240) ([marcparadise](https://github.com/marcparadise))

## [v5.0.0](https://github.com/chef/chef-zero/tree/v5.0.0) (2016-08-24)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.9.0...v5.0.0)

**Implemented enhancements:**

- Support clients and users fields in ACL PUT requests [\#239](https://github.com/chef/chef-zero/pull/239) ([marcparadise](https://github.com/marcparadise))
- Remove support for Ruby 2.1 [\#237](https://github.com/chef/chef-zero/pull/237) ([jkeiser](https://github.com/jkeiser))

## [v4.9.0](https://github.com/chef/chef-zero/tree/v4.9.0) (2016-08-11)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.8.0...v4.9.0)

**Fixed bugs:**

- Connect to chef zero default port in the playground [\#229](https://github.com/chef/chef-zero/pull/229) ([thommay](https://github.com/thommay))
- Correct ruby syntax error to make script usable [\#228](https://github.com/chef/chef-zero/pull/228) ([AntonOfTheWoods](https://github.com/AntonOfTheWoods))

## [v4.8.0](https://github.com/chef/chef-zero/tree/v4.8.0) (2016-07-25)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.7.1...v4.8.0)

**Implemented enhancements:**

- Load libraries recursively [\#227](https://github.com/chef/chef-zero/pull/227) ([thommay](https://github.com/thommay))
- Reset the ChefFS cache after each test [\#226](https://github.com/chef/chef-zero/pull/226) ([thommay](https://github.com/thommay))
- Format readme, remove waffle badges, add license [\#225](https://github.com/chef/chef-zero/pull/225) ([tas50](https://github.com/tas50))
- Return HTTP 400 Bad Request on Solr parse error [\#224](https://github.com/chef/chef-zero/pull/224) ([lamont-granquist](https://github.com/lamont-granquist))
- Set log level to debug in the rescue block. [\#222](https://github.com/chef/chef-zero/pull/222) ([maxlazio](https://github.com/maxlazio))
- support URI specific character in file name [\#204](https://github.com/chef/chef-zero/pull/204) ([byplayer](https://github.com/byplayer))
- add patch to support chef\_version [\#171](https://github.com/chef/chef-zero/pull/171) ([lamont-granquist](https://github.com/lamont-granquist))
- Update error message for daemon on Windows [\#148](https://github.com/chef/chef-zero/pull/148) ([aerii](https://github.com/aerii))
- Increase WEBrick request timeout to 300 seconds [\#138](https://github.com/chef/chef-zero/pull/138) ([kongslund](https://github.com/kongslund))
- Make ChefZero aware of load balancers [\#109](https://github.com/chef/chef-zero/pull/109) ([joshk0](https://github.com/joshk0))
- disable sslv3 and few unsecure options [\#106](https://github.com/chef/chef-zero/pull/106) ([sawanoboly](https://github.com/sawanoboly))

**Fixed bugs:**

- Fix attempted fall-through in case statement. [\#175](https://github.com/chef/chef-zero/pull/175) ([andrewdotn](https://github.com/andrewdotn))
- Fix scary search behavior on terms containing dash character [\#158](https://github.com/chef/chef-zero/pull/158) ([amazon](https://github.com/amazon))
- add normal tags with empty array [\#139](https://github.com/chef/chef-zero/pull/139) ([cl-lab-k](https://github.com/cl-lab-k))

## [v4.7.1](https://github.com/chef/chef-zero/tree/v4.7.1) (2016-07-07)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.7.0...v4.7.1)

**Implemented enhancements:**

- Downgrade info log message to debug [\#221](https://github.com/chef/chef-zero/pull/221) ([stanhu](https://github.com/stanhu))

## [v4.7.0](https://github.com/chef/chef-zero/tree/v4.7.0) (2016-06-30)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.6.2...v4.7.0)

**Implemented enhancements:**

- Add external\_authentication\_uid to actors endpoint for querying [\#217](https://github.com/chef/chef-zero/pull/217) ([kmacgugan](https://github.com/kmacgugan))

**Merged pull requests:**

- Depend on rack \< 2 to restore Ruby 2.1 compat [\#219](https://github.com/chef/chef-zero/pull/219) ([tas50](https://github.com/tas50))

## [v4.6.2](https://github.com/chef/chef-zero/tree/v4.6.2) (2016-04-28)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.6.1...v4.6.2)

**Fixed bugs:**

- Log responses only at debug log level [\#216](https://github.com/chef/chef-zero/pull/216) ([stevendanna](https://github.com/stevendanna))

## [v4.6.1](https://github.com/chef/chef-zero/tree/v4.6.1) (2016-04-14)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.6.0...v4.6.1)

**Fixed bugs:**

- Actually merge key data in user PUT response [\#214](https://github.com/chef/chef-zero/pull/214) ([jkeiser](https://github.com/jkeiser))
- Fix users endpoint in OSC compat mode to use a data store URL [\#213](https://github.com/chef/chef-zero/pull/213) ([jkeiser](https://github.com/jkeiser))

## [v4.6.0](https://github.com/chef/chef-zero/tree/v4.6.0) (2016-04-14)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.5.0...v4.6.0)

**Implemented enhancements:**

- Enable listening on more than one address [\#208](https://github.com/chef/chef-zero/pull/208) ([jaymzh](https://github.com/jaymzh))
- Implemented GET /orgs/ORG/users/USER/keys\(/key\) endpoint recently added to server. [\#205](https://github.com/chef/chef-zero/pull/205) ([tylercloke](https://github.com/tylercloke))
- Implement APIv1 behaviors [\#201](https://github.com/chef/chef-zero/pull/201) ([danielsdeleo](https://github.com/danielsdeleo))
- Make user and client keys endpoints pass Pedant specs [\#199](https://github.com/chef/chef-zero/pull/199) ([jrunning](https://github.com/jrunning))
- fix necessary for metadata gem [\#197](https://github.com/chef/chef-zero/pull/197) ([lamont-granquist](https://github.com/lamont-granquist))

**Fixed bugs:**

- Fix bugs related to Array vs Enumerator vs Port for options\[:port/host\]. [\#212](https://github.com/chef/chef-zero/pull/212) ([tylercloke](https://github.com/tylercloke))

## [v4.5.0](https://github.com/chef/chef-zero/tree/v4.5.0) (2016-01-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.4.2...v4.5.0)

**Merged pull requests:**

- Run chef-zero against master Chef in travis [\#195](https://github.com/chef/chef-zero/pull/195) ([jkeiser](https://github.com/jkeiser))
- Make ACLs for policies/policy\_groups/cookbook\_artifacts work [\#194](https://github.com/chef/chef-zero/pull/194) ([jkeiser](https://github.com/jkeiser))
- Return 410 on /controls so we stop skipping that pedant spec. [\#192](https://github.com/chef/chef-zero/pull/192) ([randomcamel](https://github.com/randomcamel))
- Enable container specs. [\#191](https://github.com/chef/chef-zero/pull/191) ([randomcamel](https://github.com/randomcamel))
- Enable headers pedant tests [\#190](https://github.com/chef/chef-zero/pull/190) ([danielsdeleo](https://github.com/danielsdeleo))
- Enable knife pedant tests [\#189](https://github.com/chef/chef-zero/pull/189) ([danielsdeleo](https://github.com/danielsdeleo))
- Start running policy and cookbook artifact tests [\#187](https://github.com/chef/chef-zero/pull/187) ([jkeiser](https://github.com/jkeiser))

## [v4.4.2](https://github.com/chef/chef-zero/tree/v4.4.2) (2016-01-15)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.4.1...v4.4.2)

**Merged pull requests:**

- Make hoovering and deleting parent dir work everywhere for cookbook\_artifacts [\#186](https://github.com/chef/chef-zero/pull/186) ([jkeiser](https://github.com/jkeiser))
- Explain why omnibus/authz/authN/validation checks are skipped [\#185](https://github.com/chef/chef-zero/pull/185) ([danielsdeleo](https://github.com/danielsdeleo))

## [v4.4.1](https://github.com/chef/chef-zero/tree/v4.4.1) (2016-01-14)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.4.0...v4.4.1)

**Merged pull requests:**

- Only test master branch and PRs [\#184](https://github.com/chef/chef-zero/pull/184) ([danielsdeleo](https://github.com/danielsdeleo))
- Internal orgs appears to be unused in oc-chef-pedant [\#183](https://github.com/chef/chef-zero/pull/183) ([danielsdeleo](https://github.com/danielsdeleo))
- Fix cookbook\_artifact rspec [\#182](https://github.com/chef/chef-zero/pull/182) ([jkeiser](https://github.com/jkeiser))
- Point chef-server back to master [\#180](https://github.com/chef/chef-zero/pull/180) ([thommay](https://github.com/thommay))
- Ignore the universe endpoint tests in pedant [\#176](https://github.com/chef/chef-zero/pull/176) ([thommay](https://github.com/thommay))

## [v4.4.0](https://github.com/chef/chef-zero/tree/v4.4.0) (2015-12-11)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.3.2...v4.4.0)

**Closed issues:**

- Please bump hashie version if possible [\#97](https://github.com/chef/chef-zero/issues/97)

**Merged pull requests:**

- ChefZero::RSpec support for cookbook\_artifacts. [\#179](https://github.com/chef/chef-zero/pull/179) ([randomcamel](https://github.com/randomcamel))
- /cookbook\_artifacts support for in-memory and FILE\_STORE backends \(not ChefFS\) [\#178](https://github.com/chef/chef-zero/pull/178) ([randomcamel](https://github.com/randomcamel))
- Update and refactor policy and policy\_groups endpoints [\#177](https://github.com/chef/chef-zero/pull/177) ([jkeiser](https://github.com/jkeiser))
- Point at master of oc-chef-pedant and chef [\#174](https://github.com/chef/chef-zero/pull/174) ([stevendanna](https://github.com/stevendanna))
- Upgrade pedant, and enable running in ChefFS mode [\#173](https://github.com/chef/chef-zero/pull/173) ([randomcamel](https://github.com/randomcamel))
- Implement the /policies and /policy\_groups API routes [\#172](https://github.com/chef/chef-zero/pull/172) ([randomcamel](https://github.com/randomcamel))
- Add gemspec files to allow bundler to run from the gem [\#169](https://github.com/chef/chef-zero/pull/169) ([ksubrama](https://github.com/ksubrama))

## [v4.3.2](https://github.com/chef/chef-zero/tree/v4.3.2) (2015-09-30)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.3.1...v4.3.2)

## [v4.3.1](https://github.com/chef/chef-zero/tree/v4.3.1) (2015-09-30)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.3.0...v4.3.1)

**Fixed bugs:**

- chefspec client creation test broken by \#117 [\#165](https://github.com/chef/chef-zero/issues/165)
- Translate admin="true" to admin=true [\#166](https://github.com/chef/chef-zero/pull/166) ([jkeiser](https://github.com/jkeiser))

## [v4.3.0](https://github.com/chef/chef-zero/tree/v4.3.0) (2015-09-02)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.2.3...v4.3.0)

**Implemented enhancements:**

- Allow Hashie to float to 3.x \(no need to be so specific\) [\#164](https://github.com/chef/chef-zero/pull/164) ([jkeiser](https://github.com/jkeiser))
- Server api version [\#155](https://github.com/chef/chef-zero/pull/155) ([andrewjamesbrown](https://github.com/andrewjamesbrown))
- Add /organizations/NAME/nodes/NAME/\_identifiers endpoint [\#152](https://github.com/chef/chef-zero/pull/152) ([andrewjamesbrown](https://github.com/andrewjamesbrown))
- CS12 Support [\#117](https://github.com/chef/chef-zero/pull/117) ([marcparadise](https://github.com/marcparadise))

**Fixed bugs:**

- Adding back logic to delete the association request when adding a user to an org \(as well as adding the user to the groups\) [\#160](https://github.com/chef/chef-zero/pull/160) ([tyler-ball](https://github.com/tyler-ball))
- Switch to pedant in chef-server repo [\#151](https://github.com/chef/chef-zero/pull/151) ([andrewjamesbrown](https://github.com/andrewjamesbrown))
- Update gem dependencies [\#146](https://github.com/chef/chef-zero/pull/146) ([andrewjamesbrown](https://github.com/andrewjamesbrown))
- Remove dependency on chef [\#140](https://github.com/chef/chef-zero/pull/140) ([terceiro](https://github.com/terceiro))

**Merged pull requests:**

- Autogenerated changelog [\#163](https://github.com/chef/chef-zero/pull/163) ([jkeiser](https://github.com/jkeiser))

## [v4.2.3](https://github.com/chef/chef-zero/tree/v4.2.3) (2015-06-19)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.2.2...v4.2.3)

**Merged pull requests:**

- Make server\_scope: :context work again [\#143](https://github.com/chef/chef-zero/pull/143) ([jkeiser](https://github.com/jkeiser))

## [v4.2.2](https://github.com/chef/chef-zero/tree/v4.2.2) (2015-05-18)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.2.1...v4.2.2)

**Merged pull requests:**

- Update version and changelog for 4.2.2 [\#134](https://github.com/chef/chef-zero/pull/134) ([danielsdeleo](https://github.com/danielsdeleo))
- Access server opts in example context not describe context [\#133](https://github.com/chef/chef-zero/pull/133) ([danielsdeleo](https://github.com/danielsdeleo))
- Adding `server\_on\_port` method to socketless server map [\#131](https://github.com/chef/chef-zero/pull/131) ([tyler-ball](https://github.com/tyler-ball))
- Ignore .ruby-version [\#98](https://github.com/chef/chef-zero/pull/98) ([raskchanky](https://github.com/raskchanky))

## [v4.2.1](https://github.com/chef/chef-zero/tree/v4.2.1) (2015-04-07)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.2.0...v4.2.1)

**Merged pull requests:**

- Don't pollute global Chef server options [\#125](https://github.com/chef/chef-zero/pull/125) ([jkeiser](https://github.com/jkeiser))

## [v4.2.0](https://github.com/chef/chef-zero/tree/v4.2.0) (2015-04-06)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.1.0...v4.2.0)

**Merged pull requests:**

- bump ffi-yajl dep [\#124](https://github.com/chef/chef-zero/pull/124) ([lamont-granquist](https://github.com/lamont-granquist))
- Add :organization and :data\_scope options to with\_chef\_server [\#119](https://github.com/chef/chef-zero/pull/119) ([jkeiser](https://github.com/jkeiser))

## [v4.1.0](https://github.com/chef/chef-zero/tree/v4.1.0) (2015-04-01)
[Full Changelog](https://github.com/chef/chef-zero/compare/v4.0...v4.1.0)

**Merged pull requests:**

- Socketless Requests [\#121](https://github.com/chef/chef-zero/pull/121) ([danielsdeleo](https://github.com/danielsdeleo))
- Partially Revert 1b2a6e5f107254cce8200a4750035b30265ae0c8 [\#120](https://github.com/chef/chef-zero/pull/120) ([danielsdeleo](https://github.com/danielsdeleo))
- Policyfile Revision ID Validation. [\#116](https://github.com/chef/chef-zero/pull/116) ([danielsdeleo](https://github.com/danielsdeleo))
- Use a Chef version compatible with chef-zero 4.x [\#115](https://github.com/chef/chef-zero/pull/115) ([danielsdeleo](https://github.com/danielsdeleo))
- Support /version; fix some global URIs [\#113](https://github.com/chef/chef-zero/pull/113) ([jaymzh](https://github.com/jaymzh))

## [v4.0](https://github.com/chef/chef-zero/tree/v4.0) (2015-02-11)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.2.1...v4.0)

**Closed issues:**

- Upgrading to chef-client 12 packages appear to break on TK's chef-zero provisioner [\#108](https://github.com/chef/chef-zero/issues/108)
- The local\_mode on chef 12.0.0.alpha.2 can't create object to local filesystem. [\#99](https://github.com/chef/chef-zero/issues/99)

**Merged pull requests:**

- Policyfile get/set API [\#111](https://github.com/chef/chef-zero/pull/111) ([danielsdeleo](https://github.com/danielsdeleo))

## [v3.2.1](https://github.com/chef/chef-zero/tree/v3.2.1) (2014-11-26)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.2.1...v3.2.1)

**Closed issues:**

- missing `else`? [\#102](https://github.com/chef/chef-zero/issues/102)

**Merged pull requests:**

- Version bump for 3.2.1. [\#105](https://github.com/chef/chef-zero/pull/105) ([sersut](https://github.com/sersut))
- fix: should set https to rack.url\_scheme \#87 [\#104](https://github.com/chef/chef-zero/pull/104) ([sawanoboly](https://github.com/sawanoboly))
- Add option for logging to a file. [\#103](https://github.com/chef/chef-zero/pull/103) ([jaymzh](https://github.com/jaymzh))
- add CORS header [\#96](https://github.com/chef/chef-zero/pull/96) ([smith](https://github.com/smith))

## [v2.2.1](https://github.com/chef/chef-zero/tree/v2.2.1) (2014-10-08)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.2...v2.2.1)

## [v3.2](https://github.com/chef/chef-zero/tree/v3.2) (2014-09-27)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.1.3...v3.2)

**Closed issues:**

- chef-zero not copying data\_bags into cache [\#83](https://github.com/chef/chef-zero/issues/83)
- Wrong generated client keys with Ruby 1.9.2 [\#65](https://github.com/chef/chef-zero/issues/65)

**Merged pull requests:**

- Removing 'json' gem dependency, replacing with 'ffi-yajl' [\#93](https://github.com/chef/chef-zero/pull/93) ([tyler-ball](https://github.com/tyler-ball))

## [v3.1.3](https://github.com/chef/chef-zero/tree/v3.1.3) (2014-09-04)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.1.2...v3.1.3)

**Merged pull requests:**

- Pass base URI to V1 data store only in true single org mode [\#89](https://github.com/chef/chef-zero/pull/89) ([jkeiser](https://github.com/jkeiser))

## [v3.1.2](https://github.com/chef/chef-zero/tree/v3.1.2) (2014-08-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.1.1...v3.1.2)

## [v3.1.1](https://github.com/chef/chef-zero/tree/v3.1.1) (2014-08-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.1...v3.1.1)

## [v3.1](https://github.com/chef/chef-zero/tree/v3.1) (2014-08-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.0...v3.1)

## [v3.0](https://github.com/chef/chef-zero/tree/v3.0) (2014-08-22)
[Full Changelog](https://github.com/chef/chef-zero/compare/v3.0.0.rc.1...v3.0)

**Implemented enhancements:**

- Make Enterprise Chef pass oc-chef-pedant [\#73](https://github.com/chef/chef-zero/issues/73)
- Add Enterprise Chef users endpoints [\#72](https://github.com/chef/chef-zero/issues/72)
- Add Enterprise Chef containers endpoints [\#71](https://github.com/chef/chef-zero/issues/71)
- Add Enterprise Chef groups endpoints [\#70](https://github.com/chef/chef-zero/issues/70)
- Add Enterprise Chef acls endpoints [\#69](https://github.com/chef/chef-zero/issues/69)
- Add Enterprise Chef organizations endpoints [\#68](https://github.com/chef/chef-zero/issues/68)

**Closed issues:**

- SSL support [\#86](https://github.com/chef/chef-zero/issues/86)

## [v3.0.0.rc.1](https://github.com/chef/chef-zero/tree/v3.0.0.rc.1) (2014-08-22)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.2...v3.0.0.rc.1)

**Closed issues:**

- Vagrant on windows fails to load Chef-Zero due to Chef dependencies [\#55](https://github.com/chef/chef-zero/issues/55)

**Merged pull requests:**

- Support ssl \(--\[no-\]ssl option\) [\#87](https://github.com/chef/chef-zero/pull/87) ([sawanoboly](https://github.com/sawanoboly))
- Get enterprise chef-zero passing oc-chef-pedant [\#84](https://github.com/chef/chef-zero/pull/84) ([jkeiser](https://github.com/jkeiser))
- waffle.io Badge [\#74](https://github.com/chef/chef-zero/pull/74) ([waffle-iron](https://github.com/waffle-iron))

## [v2.2](https://github.com/chef/chef-zero/tree/v2.2) (2014-06-18)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1.5...v2.2)

**Merged pull requests:**

- Allow server to try multiple ports [\#67](https://github.com/chef/chef-zero/pull/67) ([jkeiser](https://github.com/jkeiser))

## [v2.1.5](https://github.com/chef/chef-zero/tree/v2.1.5) (2014-06-03)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1.4...v2.1.5)

**Merged pull requests:**

- Honor :single\_org =\> 'orgname' parameter everywhere [\#66](https://github.com/chef/chef-zero/pull/66) ([jkeiser](https://github.com/jkeiser))

## [v2.1.4](https://github.com/chef/chef-zero/tree/v2.1.4) (2014-05-28)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1.3...v2.1.4)

## [v2.1.3](https://github.com/chef/chef-zero/tree/v2.1.3) (2014-05-27)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1.2...v2.1.3)

## [v2.1.2](https://github.com/chef/chef-zero/tree/v2.1.2) (2014-05-27)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1.1...v2.1.2)

## [v2.1.1](https://github.com/chef/chef-zero/tree/v2.1.1) (2014-05-27)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.1...v2.1.1)

## [v2.1](https://github.com/chef/chef-zero/tree/v2.1) (2014-05-26)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.6.3...v2.1)

**Closed issues:**

- Is there a good way to detect if cookbook is being run using chef-zero? [\#63](https://github.com/chef/chef-zero/issues/63)
- Not loading roles [\#61](https://github.com/chef/chef-zero/issues/61)
- How to handle changing url of ChefZero during chef-client run [\#59](https://github.com/chef/chef-zero/issues/59)
- data\_bag\_item fails in definition block executions [\#58](https://github.com/chef/chef-zero/issues/58)

**Merged pull requests:**

- Add multi-tenancy support and chef local mode tests [\#64](https://github.com/chef/chef-zero/pull/64) ([jkeiser](https://github.com/jkeiser))

## [v1.6.3](https://github.com/chef/chef-zero/tree/v1.6.3) (2014-02-10)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.7.3...v1.6.3)

**Closed issues:**

- chef-zero 404'ing on data bag items [\#56](https://github.com/chef/chef-zero/issues/56)
- Errno::ENAMETOOLONG [\#53](https://github.com/chef/chef-zero/issues/53)
- Backport fix for Isssue \#48 to the 1.x line [\#51](https://github.com/chef/chef-zero/issues/51)
- Search strange behavior [\#42](https://github.com/chef/chef-zero/issues/42)

## [v1.7.3](https://github.com/chef/chef-zero/tree/v1.7.3) (2014-01-22)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.0.2...v1.7.3)

**Closed issues:**

- search query fails when using parenthesis [\#38](https://github.com/chef/chef-zero/issues/38)

## [v2.0.2](https://github.com/chef/chef-zero/tree/v2.0.2) (2014-01-21)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.0.1...v2.0.2)

**Closed issues:**

- Parsing metadata blows up on evaluating metadata.json. [\#48](https://github.com/chef/chef-zero/issues/48)
- depsolve endpoint needs informative error messages [\#32](https://github.com/chef/chef-zero/issues/32)

**Merged pull requests:**

- Read JSON, not a file path [\#52](https://github.com/chef/chef-zero/pull/52) ([sethvargo](https://github.com/sethvargo))
- Fix IPV6 support [\#50](https://github.com/chef/chef-zero/pull/50) ([sethvargo](https://github.com/sethvargo))
- Fix typo [\#47](https://github.com/chef/chef-zero/pull/47) ([gregkare](https://github.com/gregkare))

## [v2.0.1](https://github.com/chef/chef-zero/tree/v2.0.1) (2014-01-03)
[Full Changelog](https://github.com/chef/chef-zero/compare/v2.0.0...v2.0.1)

**Merged pull requests:**

- Fix clear data when no data was added to chef zero [\#46](https://github.com/chef/chef-zero/pull/46) ([alex-slynko](https://github.com/alex-slynko))
- Fix an issue with an incorrect number of parameters passed to build\_uri [\#45](https://github.com/chef/chef-zero/pull/45) ([sethvargo](https://github.com/sethvargo))
- Make playground items more semantic [\#44](https://github.com/chef/chef-zero/pull/44) ([sethvargo](https://github.com/sethvargo))

## [v2.0.0](https://github.com/chef/chef-zero/tree/v2.0.0) (2013-12-17)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.7.2...v2.0.0)

**Closed issues:**

- Not found returned for all roles [\#34](https://github.com/chef/chef-zero/issues/34)

**Merged pull requests:**

- Remove puma and fork a subprocess [\#43](https://github.com/chef/chef-zero/pull/43) ([sethvargo](https://github.com/sethvargo))

## [v1.7.2](https://github.com/chef/chef-zero/tree/v1.7.2) (2013-11-19)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.7.1...v1.7.2)

**Merged pull requests:**

- Make Server Options Configurable in RSpec Helper [\#41](https://github.com/chef/chef-zero/pull/41) ([danielsdeleo](https://github.com/danielsdeleo))

## [v1.7.1](https://github.com/chef/chef-zero/tree/v1.7.1) (2013-11-03)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.7...v1.7.1)

**Implemented enhancements:**

- Find a pure-Ruby server solution [\#36](https://github.com/chef/chef-zero/issues/36)

## [v1.7](https://github.com/chef/chef-zero/tree/v1.7) (2013-11-02)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.7.beta.1...v1.7)

## [v1.7.beta.1](https://github.com/chef/chef-zero/tree/v1.7.beta.1) (2013-11-02)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.6.2...v1.7.beta.1)

**Merged pull requests:**

- improve depsolver error message [\#40](https://github.com/chef/chef-zero/pull/40) ([lamont-granquist](https://github.com/lamont-granquist))

## [v1.6.2](https://github.com/chef/chef-zero/tree/v1.6.2) (2013-10-11)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.6.1...v1.6.2)

## [v1.6.1](https://github.com/chef/chef-zero/tree/v1.6.1) (2013-10-11)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.6...v1.6.1)

**Closed issues:**

- \[\* TO \*\] search syntax doesn't work [\#37](https://github.com/chef/chef-zero/issues/37)

**Merged pull requests:**

- Range queries with smoke test [\#35](https://github.com/chef/chef-zero/pull/35) ([mattgleeson](https://github.com/mattgleeson))

## [v1.6](https://github.com/chef/chef-zero/tree/v1.6) (2013-09-13)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.6...v1.6)

## [v1.5.6](https://github.com/chef/chef-zero/tree/v1.5.6) (2013-09-13)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.5...v1.5.6)

## [v1.5.5](https://github.com/chef/chef-zero/tree/v1.5.5) (2013-08-08)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.4...v1.5.5)

**Closed issues:**

- Incorrect search behavior when a query parameter contains a '-' character [\#31](https://github.com/chef/chef-zero/issues/31)
- databag.save throws 405 "Method not allowed" [\#29](https://github.com/chef/chef-zero/issues/29)
- How can I validate if I am running in Chef-Zero mode? [\#28](https://github.com/chef/chef-zero/issues/28)
- License missing from gemspec [\#26](https://github.com/chef/chef-zero/issues/26)

**Merged pull requests:**

- fixup end\_range typos [\#30](https://github.com/chef/chef-zero/pull/30) ([mattgleeson](https://github.com/mattgleeson))
- Add license to gemspec \(fixes \#26\) [\#27](https://github.com/chef/chef-zero/pull/27) ([sethvargo](https://github.com/sethvargo))

## [v1.5.4](https://github.com/chef/chef-zero/tree/v1.5.4) (2013-07-12)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.3...v1.5.4)

**Closed issues:**

- Issue with  [\#25](https://github.com/chef/chef-zero/issues/25)
- Typo error in README [\#24](https://github.com/chef/chef-zero/issues/24)
- Add a CHANGELOG [\#11](https://github.com/chef/chef-zero/issues/11)

## [v1.5.3](https://github.com/chef/chef-zero/tree/v1.5.3) (2013-06-28)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.2...v1.5.3)

**Closed issues:**

- Chef Zero should set a server header for identification [\#23](https://github.com/chef/chef-zero/issues/23)
- Data bag search of the form "x:y AND NOT z:w" fails [\#22](https://github.com/chef/chef-zero/issues/22)

## [v1.5.2](https://github.com/chef/chef-zero/tree/v1.5.2) (2013-06-27)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5.1...v1.5.2)

## [v1.5.1](https://github.com/chef/chef-zero/tree/v1.5.1) (2013-06-19)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.5...v1.5.1)

**Closed issues:**

- Developing Vagrant-Chef-Zero [\#21](https://github.com/chef/chef-zero/issues/21)

**Merged pull requests:**

- Allow chef-zero to listen on Unix domain socket. [\#20](https://github.com/chef/chef-zero/pull/20) ([stevendanna](https://github.com/stevendanna))

## [v1.5](https://github.com/chef/chef-zero/tree/v1.5) (2013-06-12)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.4...v1.5)

**Merged pull requests:**

- Support daemon mode [\#19](https://github.com/chef/chef-zero/pull/19) ([sethvargo](https://github.com/sethvargo))

## [v1.4](https://github.com/chef/chef-zero/tree/v1.4) (2013-06-07)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.4.0.alpha...v1.4)

**Merged pull requests:**

- Downgrade Puma so Chef Zero runs on Windows [\#18](https://github.com/chef/chef-zero/pull/18) ([sethvargo](https://github.com/sethvargo))

## [v1.4.0.alpha](https://github.com/chef/chef-zero/tree/v1.4.0.alpha) (2013-06-07)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.3...v1.4.0.alpha)

**Closed issues:**

- Searching for a node with an exact name fails [\#15](https://github.com/chef/chef-zero/issues/15)

## [v1.3](https://github.com/chef/chef-zero/tree/v1.3) (2013-06-06)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.2.1...v1.3)

**Closed issues:**

- Searching is Broken [\#14](https://github.com/chef/chef-zero/issues/14)

## [v1.2.1](https://github.com/chef/chef-zero/tree/v1.2.1) (2013-06-05)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.2...v1.2.1)

**Closed issues:**

- Allow seeding of Data [\#13](https://github.com/chef/chef-zero/issues/13)

## [v1.2](https://github.com/chef/chef-zero/tree/v1.2) (2013-06-03)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.1.3...v1.2)

**Merged pull requests:**

- Fix usage info to be consistent with latest version [\#12](https://github.com/chef/chef-zero/pull/12) ([andrewgross](https://github.com/andrewgross))

## [v1.1.3](https://github.com/chef/chef-zero/tree/v1.1.3) (2013-05-30)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.1.2...v1.1.3)

## [v1.1.2](https://github.com/chef/chef-zero/tree/v1.1.2) (2013-05-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.1.1...v1.1.2)

## [v1.1.1](https://github.com/chef/chef-zero/tree/v1.1.1) (2013-05-28)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.1...v1.1.1)

**Merged pull requests:**

- fix undefined method .list on CookbookData [\#10](https://github.com/chef/chef-zero/pull/10) ([reset](https://github.com/reset))

## [v1.1](https://github.com/chef/chef-zero/tree/v1.1) (2013-05-28)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.0.1...v1.1)

## [v1.0.1](https://github.com/chef/chef-zero/tree/v1.0.1) (2013-05-20)
[Full Changelog](https://github.com/chef/chef-zero/compare/v1.0...v1.0.1)

**Merged pull requests:**

- Fix frozen version [\#9](https://github.com/chef/chef-zero/pull/9) ([sethvargo](https://github.com/sethvargo))

## [v1.0](https://github.com/chef/chef-zero/tree/v1.0) (2013-05-20)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.13...v1.0)

## [v0.9.13](https://github.com/chef/chef-zero/tree/v0.9.13) (2013-05-20)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.12...v0.9.13)

## [v0.9.12](https://github.com/chef/chef-zero/tree/v0.9.12) (2013-05-20)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.11...v0.9.12)

**Merged pull requests:**

- Move to Puma [\#8](https://github.com/chef/chef-zero/pull/8) ([sethvargo](https://github.com/sethvargo))

## [v0.9.11](https://github.com/chef/chef-zero/tree/v0.9.11) (2013-05-19)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.9...v0.9.11)

**Closed issues:**

- no port found in cookbook url - can't download cookbooks unless listening on port 80 [\#5](https://github.com/chef/chef-zero/issues/5)

**Merged pull requests:**

- Add '-d' flag [\#7](https://github.com/chef/chef-zero/pull/7) ([sethvargo](https://github.com/sethvargo))

## [v0.9.9](https://github.com/chef/chef-zero/tree/v0.9.9) (2013-05-14)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.8...v0.9.9)

**Closed issues:**

- HTTP 500 Returned when Accept Header isn't set. [\#3](https://github.com/chef/chef-zero/issues/3)
- knife plugin? [\#2](https://github.com/chef/chef-zero/issues/2)
- Cannot give a specific recipe from chef-client [\#1](https://github.com/chef/chef-zero/issues/1)

**Merged pull requests:**

- Remove dependency on Chef gem \(adds JRuby support\) [\#6](https://github.com/chef/chef-zero/pull/6) ([reset](https://github.com/reset))
- Assume application/json is acceptable if no Accept header was sent. [\#4](https://github.com/chef/chef-zero/pull/4) ([stevendanna](https://github.com/stevendanna))

## [v0.9.8](https://github.com/chef/chef-zero/tree/v0.9.8) (2013-04-29)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.7...v0.9.8)

## [v0.9.7](https://github.com/chef/chef-zero/tree/v0.9.7) (2013-04-17)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.6...v0.9.7)

## [v0.9.6](https://github.com/chef/chef-zero/tree/v0.9.6) (2013-04-17)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.5...v0.9.6)

## [v0.9.5](https://github.com/chef/chef-zero/tree/v0.9.5) (2013-01-21)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.4...v0.9.5)

## [v0.9.4](https://github.com/chef/chef-zero/tree/v0.9.4) (2013-01-18)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.3...v0.9.4)

## [v0.9.3](https://github.com/chef/chef-zero/tree/v0.9.3) (2013-01-12)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.2...v0.9.3)

## [v0.9.2](https://github.com/chef/chef-zero/tree/v0.9.2) (2012-12-31)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9.1...v0.9.2)

## [v0.9.1](https://github.com/chef/chef-zero/tree/v0.9.1) (2012-12-24)
[Full Changelog](https://github.com/chef/chef-zero/compare/v0.9...v0.9.1)

## [v0.9](https://github.com/chef/chef-zero/tree/v0.9) (2012-12-24)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
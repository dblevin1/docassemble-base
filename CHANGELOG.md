# Changelog

<!-- insertion marker -->
## [v1.4.61.2](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.61.2) - 2023-06-23

<small>[Compare with v1.4.61.1](https://github.com/dblevin1/docassemble-base/compare/v1.4.61.1...v1.4.61.2)</small>

### Added

- add signature alignment for pdf filling ([917c661](https://github.com/dblevin1/docassemble-base/commit/917c6617a011c2e2ed9daa84cf44c32a8f13bd4b) by Daniel Blevins).

## [v1.4.61.1](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.61.1) - 2023-06-21

<small>[Compare with v1.4.55.3](https://github.com/dblevin1/docassemble-base/compare/v1.4.55.3...v1.4.61.1)</small>

## [v1.4.55.3](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.55.3) - 2023-06-22

<small>[Compare with v1.4.55.2](https://github.com/dblevin1/docassemble-base/compare/v1.4.55.2...v1.4.55.3)</small>

## [v1.4.55.2](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.55.3) - 2023-06-06

<small>[Compare with v1.4.55.1](https://github.com/dblevin1/docassemble-base/compare/v1.4.55.1...v1.4.55.3)</small>

## [v1.4.55.1](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.55.1) - 2023-05-30

<small>[Compare with v1.4.52.3](https://github.com/dblevin1/docassemble-base/compare/v1.4.52.3...v1.4.55.1)</small>

## [v1.4.52.3](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.52.3) - 2023-05-26

<small>[Compare with v](https://github.com/dblevin1/docassemble-base/compare/v...v1.4.52.3)</small>

## [v](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.52.2) - 2023-05-19

<small>[Compare with v1.4.51.5](https://github.com/dblevin1/docassemble-base/compare/v1.4.51.5...v1.4.52.2)</small>

### Fixed

- fix bumpversion config ([d67497e](https://github.com/dblevin1/docassemble-base/commit/d67497efced23cee5aff38f2584bde19139e5811) by Daniel Blevins).

## [v1.4.51.5](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.51.5) - 2023-05-14

<small>[Compare with v1.4.51.4](https://github.com/dblevin1/docassemble-base/compare/v1.4.51.4...v1.4.51.5)</small>

## [v1.4.51.4](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.51.4) - 2023-05-13

<small>[Compare with v1.4.51.2](https://github.com/dblevin1/docassemble-base/compare/v1.4.51.2...v1.4.51.4)</small>

## [v1.4.51.2](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.51.2) - 2023-05-13

<small>[Compare with first commit](https://github.com/dblevin1/docassemble-base/compare/3d46ba21202eef27c80de1b1e1ecb2958a6c888d...v1.4.51.2)</small>

### Added

- add gitignore ([56b5884](https://github.com/dblevin1/docassemble-base/commit/56b58840d77cd1256eb48c6bd06efd41a1ecb85d) by Daniel Blevins).
- added all and any as jinja2 filters; fixed issue with validation messages of custom datatypes when used with show if ([8af217b](https://github.com/dblevin1/docassemble-base/commit/8af217b6c9d2c94d065ccf831465af68295ea06e) by Jonathan Pyle).
- additional pikepdf fixes ([8cbdd80](https://github.com/dblevin1/docassemble-base/commit/8cbdd806b1778dac13641854081bfb4093aa828d) by Jonathan Pyle).
- Add callable support to DACatchAll class ([bd2ed82](https://github.com/dblevin1/docassemble-base/commit/bd2ed8276c96c5a38a3243a12da33da934651803) by Quinten Steenhuis).
- address autocomplete options; hidden input type; Configuration searching ([63f3e32](https://github.com/dblevin1/docassemble-base/commit/63f3e3243fb774f8dbffbdf5404d5f794c99ec94) by Jonathan Pyle).
- Add more information to pdftk error screens ([c47455e](https://github.com/dblevin1/docassemble-base/commit/c47455e368f108344a0a18ecea810e75fbf4edf1) by Bryce Willey).
- Add Flask_Mail as a dependency of docassemble.base ([a51107b](https://github.com/dblevin1/docassemble-base/commit/a51107ba7a45ea54827cf632f67f8020184ae9a1) by Bryce Willey).
- Add aria-labelledby to solo-fields on pages ([620b3c9](https://github.com/dblevin1/docassemble-base/commit/620b3c965881215dcbe945d1836443692cf7a018) by Bryce Willey).
- Add invalidate to special review field commands ([8ac76f1](https://github.com/dblevin1/docassemble-base/commit/8ac76f1de264320c727af425edcead5a88125989) by Bryce Willey).
- added the Configuration directive allow configuration editing and the Docker environment variable DAALLOWCONFIGURATIONEDITING to control whether the administrator can edit the Configuration; added Docker environment variables DADEBUG and DAENABLEPLAYGROUND; the allow updates and enable playground directives now affect access to API endpoints ([22d0614](https://github.com/dblevin1/docassemble-base/commit/22d0614aeb6c09df4f9c57848e48d9202ece0aed) by Jonathan Pyle).
- Added pip index url and pip extra index urls; added insertion_order option for .true_values(); allow API keys to be passed as bearer tokens; removed pathlib as a dependency; yesnoradio now sets variable to None if not required and not answered; fix issues with target_number's data type; update the exports of docassemble.base.legal so that they include everything exported by docassemble.base.util; issue with review blocks where set and follow up were not recognized if using the older syntax; issue with send_email() and send_sms() not processing DAList recipients; issue with navigation sections showing already-visited sections as not visited; fixed four-second timeout problem with error action. ([5ed9abc](https://github.com/dblevin1/docassemble-base/commit/5ed9abce257294f4be095484b9f70687cf30820f) by Jonathan Pyle).
- Add a aria-label to the progress bar ([e457376](https://github.com/dblevin1/docassemble-base/commit/e457376283cdcf469b2047519082c5178ab8216b) by Bryce Willey).
- Added optgroups to manual select fields, and to without 'fields' too ([7b8a4d6](https://github.com/dblevin1/docassemble-base/commit/7b8a4d69dae392fefeef0fd865cda8a97029f96f) by Bryce Willey).
- Add a function to lookup language name from ISO 639 code ([7b98fae](https://github.com/dblevin1/docassemble-base/commit/7b98faeb77131296ca6cff9eabff0681e692d875) by Quinten Steenhuis).
- added descriptive log messages to initialize.sh; added traceback to failure to assemble API error; changed the way the restart screen deals with ajax timeouts; avoided possibly duplicative install table add row command; fixed issue with None not appearing by default in tri-state input elements; fixed issue with code-generated checkbox fields where input was not accepted ([bf2929e](https://github.com/dblevin1/docassemble-base/commit/bf2929ec764b87f5ceb5da248442e593eb651228) by Jonathan Pyle).
- additional on_failure and on_success options for DAWeb methods; random instance name for pdf_concatenate results; longer poll delay in package management UI ([5d06985](https://github.com/dblevin1/docassemble-base/commit/5d0698508634ab5ac282e787e6fa446dee41b13a) by Jonathan Pyle).
- added Jinja2 preprocessor feature; adjusted for ARM compatibility by disabling DAGoogleAPI's dependency; adjusted for xspace bug in new version of Pandoc; better removal of servers from supervisors list if they are non-responsive ([9b64bad](https://github.com/dblevin1/docassemble-base/commit/9b64bad7689bc3c4f2249e310be8dfd85a444f81) by Jonathan Pyle).
- additional input sanitizing for admin and developers ([0d7415b](https://github.com/dblevin1/docassemble-base/commit/0d7415b63161a3c46d44844bf4a3fb5a6adc42ba) by Jonathan Pyle).
- Added a new example on max in dates, to be referenced in the docs ([9359aab](https://github.com/dblevin1/docassemble-base/commit/9359aab294fb2fa0f3a53b45edd2090932635848) by Bryce Willey).
- additional fix for combobox issue ([d9ea820](https://github.com/dblevin1/docassemble-base/commit/d9ea8203f06bb65ae0d9ec5a01e94c187d23a524) by Jonathan Pyle).
- added pagination to get_user_list() and interview_list() and associated API endpoints; removed six support; persistent tasks; secret and current_info; software update order ([c7824a3](https://github.com/dblevin1/docassemble-base/commit/c7824a3788a6636650ebc949ac18e6ff4b184976) by Jonathan Pyle).
- add another label; manual_line_breaks; DADict true false methods; API sessions in /interviews ([98410a2](https://github.com/dblevin1/docassemble-base/commit/98410a2edbb93bbd294c22de41d464d67b28bdff) by Jonathan Pyle).
- Add .familiar method on Individual, not just name ([614a8d7](https://github.com/dblevin1/docassemble-base/commit/614a8d7018135f393de1cd7cd77e908a866f3bcd) by Quinten Steenhuis).
- address autocomplete and show if; PDF checkbox export value; closes #285 ([68d3544](https://github.com/dblevin1/docassemble-base/commit/68d3544bc2861598ccc91fd62609f6f2f7303df4) by Jonathan Pyle).
- add_separators; session error redirect url; as_noun change; Dockerfile does upgrade ([661c66c](https://github.com/dblevin1/docassemble-base/commit/661c66c19aba6ee12519896c65408b89709e0f22) by Jonathan Pyle).
- added phone number formatted function ([af6ffcb](https://github.com/dblevin1/docassemble-base/commit/af6ffcb31ae562eea2b7002f8e4e5fe210a7b542) by michaelhofrichterHVL).
- added hints to data representation; closes #161 ([a0c604c](https://github.com/dblevin1/docassemble-base/commit/a0c604c8862923a79284958224b85b83d7b4d226) by Jonathan Pyle).
- Added german translation file ([6b0b7dd](https://github.com/dblevin1/docassemble-base/commit/6b0b7dd1494218d484916106e71c6d452442a247) by Lino Helms).
- Add 'their' to import statement in util.py ([06e402e](https://github.com/dblevin1/docassemble-base/commit/06e402e4e96723bf3664444fc3e2cf7167dcaca0) by Jason Morris).
- add_action gathering ([660754c](https://github.com/dblevin1/docassemble-base/commit/660754c60aad32d4d80acab2dfb20afad55163d2) by Jonathan Pyle).
- Add 'other' to the genders in Individual ([3ec84fc](https://github.com/dblevin1/docassemble-base/commit/3ec84fc58ced611d57a59ee37f178e29be3bc844) by Jason Morris).
- Added pathlib dependency ([8f5e00f](https://github.com/dblevin1/docassemble-base/commit/8f5e00fed9bd1bf0ad3ea692c5d09d90b5373cfc) by Jonathan Pyle).
- Additional information in data representation of question ([d64bb1f](https://github.com/dblevin1/docassemble-base/commit/d64bb1f7362c90ca5c27332f4b9d2fdfba1b98f2) by Jonathan Pyle).
- Add numbered lists ([321b6d3](https://github.com/dblevin1/docassemble-base/commit/321b6d3fa22c11c561a5ddda383ecadd9c39b0de) by epompeii).
- Add Multiformat Lists, Paragraph Lists, and Blockquotes ([bba6054](https://github.com/dblevin1/docassemble-base/commit/bba605439822c33f246de233e0b61105c722656f) by epompeii).
- Add space for list ([cb5df42](https://github.com/dblevin1/docassemble-base/commit/cb5df42a74af4b98136784434e34c03ba77d8eb2) by epompeii).
- Add ability to format lists ([2634098](https://github.com/dblevin1/docassemble-base/commit/2634098f9991282c50653bf136b5043cac5b5876) by epompeii).
- added iterable info to pgvars ([f80a668](https://github.com/dblevin1/docassemble-base/commit/f80a66853325ea503dd334136e31088c3ddda681) by Jonathan Pyle).
- address changes; temp_url bug ([824c359](https://github.com/dblevin1/docassemble-base/commit/824c35913d506ad54f7fd6500b4a6fa9c2bc2891) by Jonathan Pyle).
- address autocomplete ([3173a72](https://github.com/dblevin1/docassemble-base/commit/3173a72b6fb4a9fe2f58636fbf3ab361bbb8d4c4) by Jonathan Pyle).
- added pypdftk dependency ([29087c4](https://github.com/dblevin1/docassemble-base/commit/29087c402113c45b55785075c17a108c5032bbb7) by Jonathan Pyle).
- Address geolocate and normalize ([954427d](https://github.com/dblevin1/docassemble-base/commit/954427da6bc77a57c6c8e5abfd3a5d5616b9299c) by Jonathan Pyle).
- additional fields for json ([5f9ecac](https://github.com/dblevin1/docassemble-base/commit/5f9ecacde4481fb814113f4fd424a9f3cc2383af) by Jonathan Pyle).
- add user page and PDF fields fix ([fdfdd60](https://github.com/dblevin1/docassemble-base/commit/fdfdd6083209e8f9194c304e3d8ae89b3c2cbd55) by Jonathan Pyle).
- address on one line ([c75633c](https://github.com/dblevin1/docassemble-base/commit/c75633cddeec99c78feeb6f42f1d190b69a90838) by Jonathan Pyle).
- added DASet ([6884886](https://github.com/dblevin1/docassemble-base/commit/68848864f9cf584691de41d12f399a1c9bc7d371) by Jonathan Pyle).
- added a comment again ([cb8db9b](https://github.com/dblevin1/docassemble-base/commit/cb8db9b109f5962b2d8eba9829bfd84389d52727) by Jonathan Pyle).
- added a comment ([c2cfb0d](https://github.com/dblevin1/docassemble-base/commit/c2cfb0dc1d356aff6ed5cd648a8261c29ccd52ac) by Jonathan Pyle).
- added traceback in debug mode ([0eb1f66](https://github.com/dblevin1/docassemble-base/commit/0eb1f663ddc01986bf60818fcb495b862f838fcd) by Jonathan Pyle).

### Fixed

- fix example interview ([870d5ed](https://github.com/dblevin1/docassemble-base/commit/870d5edc77dd47338eb5b974a7ae2736076d0c4a) by Jonathan Pyle).
- fixed default voicerss configuration ([a7f71c5](https://github.com/dblevin1/docassemble-base/commit/a7f71c53e88a3a48dad522e6dc5534444f3a0d6f) by Jonathan Pyle).
- fix issue with checkbox validation ([9d8ff60](https://github.com/dblevin1/docassemble-base/commit/9d8ff60c5cf740a37cef7080d20c2403d326138d) by Jonathan Pyle).
- fixed atomicwrites ([c7c89dd](https://github.com/dblevin1/docassemble-base/commit/c7c89dd4a3c60a78f24a01e4b2909a61c2a86979) by Jonathan Pyle).
- Fix showif for yesnofields when using labels above fields ([78e20e7](https://github.com/dblevin1/docassemble-base/commit/78e20e749592401da6676efb412354e372c9595f) by Staffan Malmgren).
- Fixes other undeclared variable references in corner cases ([e09e489](https://github.com/dblevin1/docassemble-base/commit/e09e4899150e031f10b7fe301abe541677517b58) by Bryce Willey).
- Fix trailing comma ([0085c7c](https://github.com/dblevin1/docassemble-base/commit/0085c7cbed0d51fe37bf598b87923b0f419c2897) by Quinten Steenhuis).
- fix_up expansion ([4b0c348](https://github.com/dblevin1/docassemble-base/commit/4b0c348a3a9f0db38e7567154dbd2313b2d2e121) by Jonathan Pyle).
- fix_up; uses_acroform; qpdf processing on error ([5c40a77](https://github.com/dblevin1/docassemble-base/commit/5c40a77f49127d49b3080ad3f0243f0d8fdc33f8) by Jonathan Pyle).
- fix re group level file permissions ([8162023](https://github.com/dblevin1/docassemble-base/commit/81620238945f37ab0c61a65c6e079b8846299d1e) by Jonathan Pyle).
- fixed verb conjugation issue ([efd2fc4](https://github.com/dblevin1/docassemble-base/commit/efd2fc49cc9c2b746c93af37ac7b59189a96ff5f) by Jonathan Pyle).
- Fixing circular import ([2886352](https://github.com/dblevin1/docassemble-base/commit/28863523c5ab79f4fb1e61feb77faa586f7ce9f9) by Niharika Singh).
- fix to subdoc multiple document bug ([4d1e200](https://github.com/dblevin1/docassemble-base/commit/4d1e2001b094ead64dd37105101bf4721c44ffed) by Jonathan Pyle).
- Fix typo ([859b3f1](https://github.com/dblevin1/docassemble-base/commit/859b3f15f74b946e68789b81dcb31d4d7c590579) by Quinten Steenhuis).
- fix examples ([531476a](https://github.com/dblevin1/docassemble-base/commit/531476aab5813fc6c1ed1f282e4c058d243b5491) by Jonathan Pyle).
- fix to ajax example ([698ec9c](https://github.com/dblevin1/docassemble-base/commit/698ec9c41b6b80304e5569ba0c2c30c9c7a1cb84) by Jonathan Pyle).
- fix for undefine function ([99f70a9](https://github.com/dblevin1/docassemble-base/commit/99f70a9c838c5ba575014a698e99d252fc1b359e) by Jonathan Pyle).
- Fix copy of part that overwrites docxcompose changes. ([2444f14](https://github.com/dblevin1/docassemble-base/commit/2444f144a9ae02b7e482e87386a120436539a03d) by Matthew).
- fixed yml syntax error ([90e9b40](https://github.com/dblevin1/docassemble-base/commit/90e9b40a631cf23b91c3d46490b56e349d1d2e61) by Lino Helms).
- fix to issue with actions; field numbers in error; ask_object_type and add_action; new_window sets target ([7eb657d](https://github.com/dblevin1/docassemble-base/commit/7eb657da1138615f07748d97954faab4d96b520a) by Jonathan Pyle).
- Fix for playground modules issue ([c75cf17](https://github.com/dblevin1/docassemble-base/commit/c75cf17d3d1c3ffd45fc628ba144c68ba100f47d) by Jonathan Pyle).
- Fixing circularity in LibreOffice initialization ([1bfb9b4](https://github.com/dblevin1/docassemble-base/commit/1bfb9b440d3e4e605ca7aa0e5748d862ab61cc5b) by Jonathan Pyle).
- fix for unicode issue in markdown documents ([ea2d7f5](https://github.com/dblevin1/docassemble-base/commit/ea2d7f57dde444d5d85dbc99d7c93f03f19678c4) by Jonathan Pyle).
- fix for exporting tables; space_to_underscore change; rows option for text area; spinner on action ([13ae5b9](https://github.com/dblevin1/docassemble-base/commit/13ae5b994c5beb6bbe0bd0cbef54b64ddc6b32f9) by Jonathan Pyle).
- fixes and enhancements for review blocks, tables, navigation bar, reconsider function, slice method ([d7f3f23](https://github.com/dblevin1/docassemble-base/commit/d7f3f231034123d487dc1b3f6c3fbefd02dd3736) by Jonathan Pyle).
- Fix Single Newlines ([65496da](https://github.com/dblevin1/docassemble-base/commit/65496da99733b840389f684d35f51948e92b0198) by epompeii).
- fix error with interview_url ([47dc1c1](https://github.com/dblevin1/docassemble-base/commit/47dc1c1b3f3d0bf7445c1d27157dd1b73bb90a9e) by Jonathan Pyle).
- fix for error with template variables using string indices; start of changes for redaction feature ([15ead95](https://github.com/dblevin1/docassemble-base/commit/15ead95ea307ce60e7f47249cccc425bd2a70ff5) by Jonathan Pyle).
- Fix outdated package notice ([d27f570](https://github.com/dblevin1/docassemble-base/commit/d27f570cb912e32f748c40220fbe3d82f51f2fbe) by Ari Chivukula).
- fixed to error notifications ([538fdb4](https://github.com/dblevin1/docassemble-base/commit/538fdb40f7a36fbf4abe44386ca9826d998d11e3) by Jonathan Pyle).
- fix uid problem ([bb08f04](https://github.com/dblevin1/docassemble-base/commit/bb08f045608d764ad10219e1d3a26d472f7e5f51) by Jonathan Pyle).
- fixed age_in_years method ([5d7bc22](https://github.com/dblevin1/docassemble-base/commit/5d7bc2264f9d1f2ccb0429a93252e15225a6b59e) by Jonathan Pyle).
- fixed docx formatting error ([3f8d657](https://github.com/dblevin1/docassemble-base/commit/3f8d657821357d4bb559a3b6f0893d18f0e60f08) by Jonathan Pyle).
- fix attachment generation problem ([2834946](https://github.com/dblevin1/docassemble-base/commit/2834946017bef9f41df1427f5144b96dff48e9e7) by Jonathan Pyle).
- fix label text error ([74ad4b8](https://github.com/dblevin1/docassemble-base/commit/74ad4b8e82d784226c362a84dc7cc8b8e5842c19) by Jonathan Pyle).
- fix to process_selections, field parsing ([a3ad5fc](https://github.com/dblevin1/docassemble-base/commit/a3ad5fcbeafe7b9b219d86e5846e52aa0504e351) by Jonathan Pyle).
- fixes of filename handling ([5028735](https://github.com/dblevin1/docassemble-base/commit/50287355f0785195cbace629c466619bc2758c04) by Jonathan Pyle).
- fix CSS typo ([3b1229d](https://github.com/dblevin1/docassemble-base/commit/3b1229d9dfd800c1ca8aa70af59aa62945d0d69f) by Jonathan Pyle).
- fix problem with DADict from checkboxes ([d1ef54f](https://github.com/dblevin1/docassemble-base/commit/d1ef54ffd7fbba03f7ee2b9981f11bca18df303d) by Jonathan Pyle).
- fix to url finder function ([b6b918f](https://github.com/dblevin1/docassemble-base/commit/b6b918f7e91bc5c1e6b5a23fde914a77f6e497fb) by Jonathan Pyle).
- fix edit user profile page error ([75accf0](https://github.com/dblevin1/docassemble-base/commit/75accf0cec2e6eb18374b90982ee58c1a90573f2) by Jonathan Pyle).
- fix Google login ([249d5f8](https://github.com/dblevin1/docassemble-base/commit/249d5f8a8990a7fd4e86ce3207409d83a8220439) by Jonathan Pyle).
- Fixed update secret problem ([f53e8cd](https://github.com/dblevin1/docassemble-base/commit/f53e8cd1a24e835932cae8c3bd7b8a2324927c67) by Jonathan Pyle).
- fix_punctuation ([0024076](https://github.com/dblevin1/docassemble-base/commit/0024076fa253f33628f5bfddac814e85d1b14d8c) by Jonathan Pyle).
- fix attorney.yml example ([3276d88](https://github.com/dblevin1/docassemble-base/commit/3276d8849c078a71979e39fa9efeb350d5718861) by Jonathan Pyle).
- fixed unicode issue with loading Markdown files ([fde51c7](https://github.com/dblevin1/docassemble-base/commit/fde51c7080a5e3f9a0ea796176c9b649c4a95c6f) by Jonathan Pyle).
- fix playground ([67fc556](https://github.com/dblevin1/docassemble-base/commit/67fc55628cdeff87866a2afea663fd2c7578a8cd) by Jonathan Pyle).
- fix chrome problem ([8f7944d](https://github.com/dblevin1/docassemble-base/commit/8f7944d8b36fbc5f9a5ec4888b02201590e083da) by Jonathan Pyle).
- fixed problem with disabling button ([99c3a2a](https://github.com/dblevin1/docassemble-base/commit/99c3a2a4fb22f53a04a1de706129f2711dbdbfa3) by Jonathan Pyle).
- fixed DAList ([5d476a5](https://github.com/dblevin1/docassemble-base/commit/5d476a5836b53c209a55cf06906be09d90e5059b) by Jonathan Pyle).
- fix playground template file problem ([9bbfa76](https://github.com/dblevin1/docassemble-base/commit/9bbfa76725956b7eacff7b71335fefebb2ae8859) by Jonathan Pyle).
- fix exec lambda combo ([d399eb7](https://github.com/dblevin1/docassemble-base/commit/d399eb7761bd0504cecb2941f157608c4796e1ab) by Jonathan Pyle).
- fix template ([06139aa](https://github.com/dblevin1/docassemble-base/commit/06139aa45d546edc706be4503f0fcbf6a14be36c) by Jonathan Pyle).
- fix capitalization issue ([40170fc](https://github.com/dblevin1/docassemble-base/commit/40170fcae06cf27a88a8ea593ad6d567dcaaa640) by Jonathan Pyle).
- fixed up example yaml files ([ff62fb8](https://github.com/dblevin1/docassemble-base/commit/ff62fb850cd46d285d86c102ee2e6d652366bd4c) by Jonathan Pyle).
- fix repr problem ([c02e3ee](https://github.com/dblevin1/docassemble-base/commit/c02e3eeb0885684141e4d9427a6e250b171c5558) by Jonathan Pyle).
- fixed login bugs; auto user creation ([37949e2](https://github.com/dblevin1/docassemble-base/commit/37949e29b28dfcfe307a2434a9102df1a0a81fe3) by Jonathan Pyle).
- fixes ([2937c2a](https://github.com/dblevin1/docassemble-base/commit/2937c2a655ac8c83fea8a64db8889efc0f3fed0a) by Jonathan Pyle).
- fixes to signature ([7edca1b](https://github.com/dblevin1/docassemble-base/commit/7edca1b5f6a8597f2db54faa8dd292d97396391a) by Jonathan Pyle).

### Changed

- changes suggested by linter; check in now sends _changed and _initial; prior keyword argument for defined, value, and showifdef; output of countries_list() and states_list() now sorted; states_list() returns empty dictionary on error; support for updating dropdown choices with background_response(); upgraded pikepdf ([e8aaf1a](https://github.com/dblevin1/docassemble-base/commit/e8aaf1a171acf6e6f72b08550639df632f6be114) by Jonathan Pyle).
- change to objects from file block so that it does not act like a mandatory block; restore encryption functionality of concatenate_files ([121d44b](https://github.com/dblevin1/docassemble-base/commit/121d44b750ad90e39e0e060fda8039c398017544) by Jonathan Pyle).
- changes suggested by linter ([0ffaff2](https://github.com/dblevin1/docassemble-base/commit/0ffaff2909e39370a106e584e709810652e024cc) by Jonathan Pyle).
- change all_variables so it respects include_internal; add required and aria-required tags; change interview_url so that it accepts only a session; change url_ask so that it can begin with an action and the action does not run twice; fix error in session deletion code ([3ff1ecf](https://github.com/dblevin1/docassemble-base/commit/3ff1ecf112bd8976c30d68ae3bbfdedfb256ad1e) by Jonathan Pyle).
- Changed other places that DocxTemplate was referenced ([75c245d](https://github.com/dblevin1/docassemble-base/commit/75c245d81d5fa2a04677d7faf8b6ebb934f952fa) by Bryce Willey).
- changes suggested by linter; API key encryption; admin user context for module loading; Bootstrap typo; machine learning fix ([98626b4](https://github.com/dblevin1/docassemble-base/commit/98626b43c3c0876eae055d3c4d16f0f8355b60ac) by Jonathan Pyle).
- changelog; startup hook ([f44d318](https://github.com/dblevin1/docassemble-base/commit/f44d3180ac54c9263d91dfe1a9345d33c44d4ddf) by Jonathan Pyle).
- change_numbering option ([7552b50](https://github.com/dblevin1/docassemble-base/commit/7552b506e35773fae2ff0cf974ab12bbe6820979) by Jonathan Pyle).
- changelog ([2cbdfd0](https://github.com/dblevin1/docassemble-base/commit/2cbdfd03b8e6a735f92ab6d5fb74b9591bfec381) by Jonathan Pyle).
- Changes for #296 ([660cc72](https://github.com/dblevin1/docassemble-base/commit/660cc7270cdac5b6be89dc92185fe8aec8bcc063) by Jonathan Pyle).
- Change to french translation for 'Clear' ([42b2b78](https://github.com/dblevin1/docassemble-base/commit/42b2b787085e7fcc4d5ffd49e262ed9b7a411820) by Michael Alpert-Appell).
- Change Spanish of "retroceder" to "Altras" ([eea85c9](https://github.com/dblevin1/docassemble-base/commit/eea85c99ea56000908717f44f5236b47732c91d2) by Toma).
- changed example ([bcfccc5](https://github.com/dblevin1/docassemble-base/commit/bcfccc548315f5078c2f48bc49b0efbb40cba611) by Jonathan Pyle).
- changelog; start of table reorder feature ([5af5030](https://github.com/dblevin1/docassemble-base/commit/5af50304f3f5109df50decc94df13c54d8566376) by Jonathan Pyle).
- Changes for Python 3; fix to foreign key problem ([56d0b30](https://github.com/dblevin1/docassemble-base/commit/56d0b30d3da9ea71b221c4d8773b915b10ad91b1) by Jonathan Pyle).
- Changes for API interview driving ([4948c39](https://github.com/dblevin1/docassemble-base/commit/4948c39ec72d5f14d8a1fe966d7cdaa1eb5ea40b) by Jonathan Pyle).
- changelog; rollback celery ([c8650f2](https://github.com/dblevin1/docassemble-base/commit/c8650f2a848e2966699411fe38949c71a634966c) by Jonathan Pyle).
- change to group gathering ([b01f031](https://github.com/dblevin1/docassemble-base/commit/b01f0311d26e068485229b885733c876ec10a4c6) by Jonathan Pyle).

### Removed

- removed dependency on py; changes suggested by CodeQL and pylint ([3928d84](https://github.com/dblevin1/docassemble-base/commit/3928d848ff414fe4d2d2c6503878e30db23b0d16) by Jonathan Pyle).
- remove warning about email template ([f2a191b](https://github.com/dblevin1/docassemble-base/commit/f2a191b6108b4315c8a86335a4e79a36eb507e2d) by Jonathan Pyle).
- Removed str_for_op, no longer used ([085b15e](https://github.com/dblevin1/docassemble-base/commit/085b15e0463745db3dba9cda6cfbe2f7dd92f474) by Bryce Willey).
- Removed calls to `long`, which no longer exists ([039ebcf](https://github.com/dblevin1/docassemble-base/commit/039ebcf097ee0d75e1c41200ad4148b94ad99da8) by Bryce Willey).
- Remove unused imports ([656990e](https://github.com/dblevin1/docassemble-base/commit/656990eeb506847abc7ca3239f2450d944e68a57) by Bryce Willey).
- Remove unnecessary semicolons ([3cbb8a0](https://github.com/dblevin1/docassemble-base/commit/3cbb8a0947f9dc2a81380d22210b2f48c6467cb8) by Bryce Willey).
- removed extraneous file ([a277f28](https://github.com/dblevin1/docassemble-base/commit/a277f282ed0f4e5203f7edb0aa2c072bbd8b4a0a) by Jonathan Pyle).
- Removed Python 2.7 compatibility code ([f1230a5](https://github.com/dblevin1/docassemble-base/commit/f1230a53888dec36628a28a74a73a39f8b6b30c0) by Jonathan Pyle).
- removed old CORS code ([37920cf](https://github.com/dblevin1/docassemble-base/commit/37920cf9862e43dc92dd1044359e3e5f31e5afae) by Jonathan Pyle).
- removed include_privileges option for get_user_list ([8b7e138](https://github.com/dblevin1/docassemble-base/commit/8b7e1380fb7829dad5f5dda9ad75709a1f9667b1) by Jonathan Pyle).
- Removed extraneous files ([e8a42a3](https://github.com/dblevin1/docassemble-base/commit/e8a42a374173044fd304595a663d9ebaf63fe778) by Jonathan Pyle).
- removed old directory of test files ([b941930](https://github.com/dblevin1/docassemble-base/commit/b941930ed7b19985b8ddb6fd3344f1ac8a4428f6) by Jonathan Pyle).
- Remove debug ([92d56f1](https://github.com/dblevin1/docassemble-base/commit/92d56f10225fb6acf336c18d20ed1fb162adce0b) by epompeii).
- removed debugging code ([0e1eba6](https://github.com/dblevin1/docassemble-base/commit/0e1eba62f30618db3babdc9406f4da2123a5bf40) by Jonathan Pyle).
- removed messages ([b01922b](https://github.com/dblevin1/docassemble-base/commit/b01922ba3557cd30043cccddeaeded05915c26d7) by Jonathan Pyle).
- removed temporary file ([53ac223](https://github.com/dblevin1/docassemble-base/commit/53ac223b6e95a2ec5eca62775396f0a64f77de6e) by Jonathan Pyle).
- remove newlines from email subject ([fbff59e](https://github.com/dblevin1/docassemble-base/commit/fbff59e298ad2605d41227ed22614a7b3c1fbb04) by Jonathan Pyle).
- remove log message ([08190b9](https://github.com/dblevin1/docassemble-base/commit/08190b9466347f246eff818868556fe1fcd6cab8) by Jonathan Pyle).
- removed pyrtf-ng dependency ([5cfe337](https://github.com/dblevin1/docassemble-base/commit/5cfe3377572739bfd63a20069d1baf2e26c2ce04) by Jonathan Pyle).
- removed comment ([de8ca41](https://github.com/dblevin1/docassemble-base/commit/de8ca41f20e5ffa6bb4d85cd6b45d341bf601ebc) by Jonathan Pyle).
- remove current_info dict ([fb10a09](https://github.com/dblevin1/docassemble-base/commit/fb10a09985d6e4d4bb4369e91b4b2a914f7e2401) by Jonathan Pyle).
- removed GPL software ([94b5477](https://github.com/dblevin1/docassemble-base/commit/94b547766594873cbfb6e1060eb3f1657b528abc) by Jonathan Pyle).

## [v1.4.52.1](https://github.com/dblevin1/docassemble-base/releases/tag/v1.4.52.1) - 2023-05-19

<small>[Compare with v1.4.51.5](https://github.com/dblevin1/docassemble-base/compare/v1.4.51.5...v1.4.52.1)</small>

### Fixed

- fix bumpversion config ([d67497e](https://github.com/dblevin1/docassemble-base/commit/d67497efced23cee5aff38f2584bde19139e5811) by Daniel Blevins).

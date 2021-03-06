# Change Log

## [v3.1.0](https://github.com/jloh/nagios-nrpe-server/tree/v3.1.0) (2019-04-08)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v3.0.1...v3.1.0)

**Implemented enhancements:**

- Add aarch64 config for ARM based RedHat/Amazon Linux installs [\#25](https://github.com/jloh/nagios-nrpe-server/pull/25) ([thowat](https://github.com/thowat))
- Allow variable override to work with OS defaults [\#24](https://github.com/jloh/nagios-nrpe-server/pull/24) ([benagricola](https://github.com/benagricola))
- enable server\_address and disable example commands in nrpe.cfg template [\#22](https://github.com/jloh/nagios-nrpe-server/pull/22) ([MrTango](https://github.com/MrTango))

**Fixed bugs:**

- nagios-plugins aren't installed on debain based OS' [\#23](https://github.com/jloh/nagios-nrpe-server/issues/23)
- Custom variables overwritten [\#18](https://github.com/jloh/nagios-nrpe-server/issues/18)
- enable server\\_address and disable example commands in nrpe.cfg template [\#22](https://github.com/jloh/nagios-nrpe-server/pull/22) ([MrTango](https://github.com/MrTango))

**Closed issues:**

- Ansible 2.X mega issue [\#16](https://github.com/jloh/nagios-nrpe-server/issues/16)

**Merged pull requests:**

- Fix lint errors [\#28](https://github.com/jloh/nagios-nrpe-server/pull/28) ([jloh](https://github.com/jloh))
- Setup CircleCI for tests [\#27](https://github.com/jloh/nagios-nrpe-server/pull/27) ([jloh](https://github.com/jloh))
- Fix var usage for aarch64 after \#24 [\#26](https://github.com/jloh/nagios-nrpe-server/pull/26) ([jloh](https://github.com/jloh))

## [v3.0.1](https://github.com/jloh/nagios-nrpe-server/tree/v3.0.1) (2017-03-25)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v3.0.0...v3.0.1)

**Implemented enhancements:**

- Nrpe command template [\#19](https://github.com/jloh/nagios-nrpe-server/pull/19) ([bashrc666](https://github.com/bashrc666))

**Fixed bugs:**

- nagios\_nrpe\_command is undefined [\#20](https://github.com/jloh/nagios-nrpe-server/issues/20)

## [v3.0.0](https://github.com/jloh/nagios-nrpe-server/tree/v3.0.0) (2016-02-27)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.3.0...v3.0.0)

**Implemented enhancements:**

- Allow comma separated server names in "nagios\_nrpe\_server\_allowed\_hosts" [\#13](https://github.com/jloh/nagios-nrpe-server/issues/13)
- Remove dependency on EPEL repo [\#9](https://github.com/jloh/nagios-nrpe-server/issues/9)

**Merged pull requests:**

- Move several tasks into single ones [\#17](https://github.com/jloh/nagios-nrpe-server/pull/17) ([jloh](https://github.com/jloh))

## [v2.3.0](https://github.com/jloh/nagios-nrpe-server/tree/v2.3.0) (2015-09-04)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.2.0...v2.3.0)

**Implemented enhancements:**

- Solaris 11.1 -- OpenCSW [\#12](https://github.com/jloh/nagios-nrpe-server/pull/12) ([jaymell](https://github.com/jaymell))

**Closed issues:**

- hardcoded sudo [\#11](https://github.com/jloh/nagios-nrpe-server/issues/11)

**Merged pull requests:**

- Add a Gitter chat badge to README.md [\#10](https://github.com/jloh/nagios-nrpe-server/pull/10) ([gitter-badger](https://github.com/gitter-badger))

## [v2.2.0](https://github.com/jloh/nagios-nrpe-server/tree/v2.2.0) (2015-04-15)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.1.1...v2.2.0)

**Implemented enhancements:**

- Ability to deploy per-server plugins [\#4](https://github.com/jloh/nagios-nrpe-server/issues/4)
- Closes \#4 - Adding the ability to deploy per-server plugins [\#8](https://github.com/jloh/nagios-nrpe-server/pull/8) ([jloh](https://github.com/jloh))
- CI test [\#7](https://github.com/jloh/nagios-nrpe-server/pull/7) ([jloh](https://github.com/jloh))
- Add Arch Linux support [\#5](https://github.com/jloh/nagios-nrpe-server/pull/5) ([k0ste](https://github.com/k0ste))

**Merged pull requests:**

- Further code cleanup [\#6](https://github.com/jloh/nagios-nrpe-server/pull/6) ([jloh](https://github.com/jloh))

## [v2.1.1](https://github.com/jloh/nagios-nrpe-server/tree/v2.1.1) (2015-01-04)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.1.0...v2.1.1)

## [v2.1.0](https://github.com/jloh/nagios-nrpe-server/tree/v2.1.0) (2015-01-04)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.0.2...v2.1.0)

**Implemented enhancements:**

- Adding task to copy plugins to hosts [\#3](https://github.com/jloh/nagios-nrpe-server/pull/3) ([jloh](https://github.com/jloh))

## [v2.0.2](https://github.com/jloh/nagios-nrpe-server/tree/v2.0.2) (2015-01-04)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.0.1...v2.0.2)

**Fixed bugs:**

- Fixing file names to match ansible vars - thanks romanlv! [\#2](https://github.com/jloh/nagios-nrpe-server/pull/2) ([jloh](https://github.com/jloh))

## [v2.0.1](https://github.com/jloh/nagios-nrpe-server/tree/v2.0.1) (2014-10-26)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v2.0.0...v2.0.1)

## [v2.0.0](https://github.com/jloh/nagios-nrpe-server/tree/v2.0.0) (2014-09-21)
[Full Changelog](https://github.com/jloh/nagios-nrpe-server/compare/v1.0.0...v2.0.0)

## [v1.0.0](https://github.com/jloh/nagios-nrpe-server/tree/v1.0.0) (2014-08-31)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
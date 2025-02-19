# Changes to RHEL8STIG

## Release 2.8.5
- updated to /var/log mount check
- added commnets for /mnt and removeable media on Azure systems

## Release 2.8.4

- ansible version updated to 2.10.1 minimum
- updated to ansible user check for passwd rule 010380
  - thanks to discord community member PoundsOfFlesh
- update readme layout and latest audit example
- changed disruptive back to false to allow users to control the settings

## Release 2.8.3

- improvements to openssh configs and seperated tasks

## Release 2.8.2

- updates to pamd logic thanks to @JacobBuskirk for highlighting

 Also following issues/PRs

- #168
- #169
- #170
- #171
- #172
- #177
- #178
- #179
- #180
- #181

## Release 2.8.0

- updates to workflow
  - ami
  - update to actions to latest versions
  - update_galaxy workflow added
- README alignment
- ansible.cfg added showing how tested
- audit template updated
- moved warnihg statements arounf for reboot

- RULEID reference updated
- 010510 rule no longer required
- 010671 improvement
- 020040 loop added
- 040090 - var typo fixed
- 040342 new control for FIP_KEX Algorithms
  - new FIPS_KEX_ALGO variable

## Release 2.7.0

- lint updates
- Benchmark 1.8 Updates
  - New RULEID for the following, plus additional notes if needed
    - CAT1
      - RHEL-08-010000
    - CAT2
      - RHEL-08-010040
      - RHEL-08-010090
      - RHEL-08-010200 - Updated keep alive count max to 1
      - RHEL-08-010201
      - RHEL-08-010360
      - RHEL-08-010372 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010373 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010373 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010374 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010375 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010376 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010383
      - RHEL-08-010384
      - RHEL-08-010430 - Updated to include find and remove for conflicting parameters
      - RHEL-08-010400
      - RHEL-08-010500
      - RHEL-08-010510
      - RHEL-08-010520
      - RHEL-08-010521
      - RHEL-08-010522
      - RHEL-08-010550
      - RHEL-08-010671
      - RHEL-08-010830
      - RHEL-08-020330
      - RHEL-08-020090
      - RHEL-08-020104
      - RHEL-08-020110
      - RHEL-08-020120
      - RHEL-08-020130
      - RHEL-08-020140
      - RHEL-08-020150
      - RHEL-08-020160
      - RHEL-08-020170
      - RHEL-08-020190
      - RHEL-08-020221
      - RHEL-08-020230
      - RHEL-08-010280
      - RHEL-08-020300
      - RHEL-08-020350 - Updated CCI
      - RHEL-08-020352
      - RHEL-08-040127 - Added tasks to deal with different versions of RHEL8
      - RHEL-08-040161
      - RHEL-08-040209 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040210 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040220 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040230 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040239 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040240 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040249 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040250 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040259 - Updated to included find and remove for conflicting parameters
      - RHEL-08-040260 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040261 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040262 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040270 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040279 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040280 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040281 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040282 - Updated to include find and remove for conflicting parameters
      - RHEL-08-040283 - Updated to include find adn remove for conflicting parameters
      - RHEL-08-040284 - Updated to include find adn remove for conflicting parameters
      - RHEL-08-040285 - Updated to include find adn remove for conflicting parameters
      - RHEL-08-040286 - Updated to include find adn remove for conflicting parameters
      - RHEL-08-040340
      - RHEL-08-040341
      - RHEL-08-040400 - New control
    - CAT3
      - RHEL-08-020340 - Updated CCI

# Release 6.1

* Update JDK version for sonarcloud
* GetDisplayName from PrincipalExtensions now uses Identity.Name, then upn claim and finally falls back on sub claim.  Fixes issue with IdentityServer showing different name as logged in user sometimes.

|Commit|Date|Author|Message|
|---|---|---|---|
| 447f46f0 | <span style="white-space:nowrap;">2023-11-29</span> | <span style="white-space:nowrap;">Cort Schaefer</span> |  use upn claim before relegating to sub claim for name; update jdk version for sonar
| ff5ac05b | <span style="white-space:nowrap;">2024-01-09</span> | <span style="white-space:nowrap;">Cort Schaefer</span> |  update latest powershell script
| ca6c7b00 | <span style="white-space:nowrap;">2024-01-09</span> | <span style="white-space:nowrap;">Cort Schaefer</span> |  Merge branch 'master' into develop
| 85fbccb3 | <span style="white-space:nowrap;">2024-01-09</span> | <span style="white-space:nowrap;">Cort Schaefer</span> |  start changelog
| 6df5e546 | <span style="white-space:nowrap;">2024-01-09</span> | <span style="white-space:nowrap;">Cort Schaefer</span> |  (HEAD -> release/6.1, origin/develop, develop) start changelog
****



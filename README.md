# GL-Turnovers-pack-for-NAV
Include G/L, Customer and Vendors turnovers from RU localization of Dynamics NAV. Made as extension, and can be published to any other NAV localization.

Publish-NAVApp  -Path $YourPath\Turnovers pack.navx  -ServerInstance $NavServer  -SkipVerification   
 
Install-NAVApp -ServerInstance $NavServer -Tenant Default -Name Turnovers Pack

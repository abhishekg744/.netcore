references --
          https://codebrains.io/how-to-add-jwt-authentication-to-asp-net-core-api-with-identityserver-4-part-1/

          https://github.com/JamesCoonce/TokenAuthASPCore/blob/master/TokenAuthASPCore/Services/IdentityClaimsProfileService.cs


modifying ApplicationDBContext file for custom tables

          -- after adding custom code delete migration folder from project and DB from sql server.
           -- run following package manager console
                  Add-Migration InitialCreate
                  Update-Database

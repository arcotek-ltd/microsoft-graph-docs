---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new AuthorizationPolicy();
$defaultUserRolePermissions = new DefaultUserRolePermissions();
$defaultUserRolePermissions->setAllowedToCreateApps(false);


$requestBody->setDefaultUserRolePermissions($defaultUserRolePermissions);


$result = $graphServiceClient->policies()->authorizationPolicyById('authorizationPolicy-id')->patch($requestBody);


```
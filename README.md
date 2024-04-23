# Spryker Feature: Marketplace MerchantPortal Core

Marketplace MerchantPortal Core enables server configuration and the basic functionality of the Merchant Portal such as security login. (Login URL is http://mp.de.spryker.local/security-merchant-portal-gui/login)

[Learn more](https://docs.spryker.com/docs/pbc/all/merchant-management/202307.0/marketplace/marketplace-merchant-portal-core-feature-overview/marketplace-merchant-portal-core-feature-overview.html)

## Installation

```
composer require spryker-feature/marketplace-merchantportal-core
```

## Recommended feature dependencies
- [spryker-feature/acl](https://github.com/spryker-feature/acl)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [AclMerchantPortalExtension ^1.0.0](https://github.com/spryker/acl-merchant-portal-extension) (Extension)
- [DashboardMerchantPortalGui ^3.0.0](https://github.com/spryker/dashboard-merchant-portal-gui) (MP GUI)
- [DashboardMerchantPortalGuiExtension ^1.0.0](https://github.com/spryker/dashboard-merchant-portal-gui-extension) (Extension)
- [MerchantUserExtension ^1.1.0](https://github.com/spryker/merchant-user-extension) (Extension)
- [SecurityBlockerMerchantPortalGui ^1.1.0](https://github.com/spryker/security-blocker-merchant-portal-gui) (MP GUI)
- [SecurityMerchantPortalGuiExtension ^1.1.0](https://github.com/spryker/security-merchant-portal-gui-extension) (Extension)
- [UserMerchantPortalGuiExtension ^1.0.0](https://github.com/spryker/user-merchant-portal-gui-extension) (Extension)

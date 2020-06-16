# AZ-500: Secure data and applications (30-35%)

## Configure Security Policies to Manage Data

* [Configure Data Classification](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/govern/policy-compliance/data-classification) | [Tutorial](https://docs.microsoft.com/en-us/azure/information-protection/infoprotect-settings-tutorial)
* [Configure Data Retention](https://docs.microsoft.com/en-us/rest/api/storageservices/setting-a-storage-analytics-data-retention-policy) | [Learn about retention policies](https://docs.microsoft.com/en-us/microsoft-365/compliance/retention-policies?view=o365-worldwide)
* [Configure Data Sovereignty](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)
* [Azure customer data protection](https://docs.microsoft.com/en-us/azure/security/fundamentals/protection-customer-data)

## Configure Security for Data Infrastructure

* [Enable Database Authentication](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication)
* [Enable Database Auditing](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing)
* [Configure Azure SQL Database Advanced Threat Protection](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-threat-detection) | [Overview](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-threat-detection-overview)
* [Configure Access Control for Storage Accounts](https://docs.microsoft.com/en-us/azure/storage/blobs/security-recommendations)
* [Configure Key Management for Storage Accounts](https://docs.microsoft.com/en-us/azure/storage/common/storage-account-keys-manage)
* [Configure Azure AD Authentication for Azure Storage](https://docs.microsoft.com/en-us/azure/storage/common/storage-auth-aad)
* [Configure Azure AD Domain Services Authentication for Azure Files](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-active-directory-enable)
* [Create and manage Shared Access Signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview)
* [Configure security for HDInsights](https://docs.microsoft.com/en-us/azure/hdinsight/domain-joined/apache-domain-joined-architecture)
* [Configure security for Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/database-security)
* [Configure security for Azure Data Lake](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control) | [Gen1](https://docs.microsoft.com/en-us/azure/data-lake-store/data-lake-store-security-overview)

## Configure Encryption for Data at Rest

* [Implement Azure SQL Database Always Encrypted](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-always-encrypted)
* [Implement Database Encryption - Transparent Data Encryption (TDE)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/transparent-data-encryption)
* [Implement Storage Service Encryption](https://docs.microsoft.com/en-us/azure/storage/common/storage-service-encryption)
* [Implement Disk Encryption](https://docs.microsoft.com/en-us/azure/security/fundamentals/azure-disk-encryption-vms-vmss)

## Configure Application Security

* [Configure SSL/TLS certs](https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-configure-ssl-certificate-portal) | [Configure TLS mutual authentication for Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-configure-tls-mutual-auth)
* [Configure Azure services to protect web apps](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-app-services)
* [Create an application security baseline](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-deployments)

## Configure and Manage Key Vault

* Manage [access to Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-secure-your-key-vault) | [Configure Azure Key Vault firewalls and virtual networks](https://docs.microsoft.com/en-us/azure/key-vault/general/network-security)
* Manage permissions to:
    * [Secrets](https://docs.microsoft.com/en-us/azure/key-vault/about-keys-secrets-and-certificates#key-vault-secrets)
    * [Certificates](https://docs.microsoft.com/en-us/azure/key-vault/about-keys-secrets-and-certificates#key-vault-certificates)
    * [Keys](https://docs.microsoft.com/en-us/azure/key-vault/about-keys-secrets-and-certificates#key-vault-keys)
* Configure [RBAC usage in Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/overview-security)
* Manage [Certificates](https://docs.microsoft.com/en-us/azure/key-vault/certificate-scenarios)
* Manage [Secrets](https://docs.microsoft.com/en-us/azure/key-vault/about-keys-secrets-and-certificates#key-vault-certificates)
* Configure [Key Rotation](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-key-rotation-log-monitoring#key-rotation-using-azure-automation)

[Return to Table of Contents](README.md)
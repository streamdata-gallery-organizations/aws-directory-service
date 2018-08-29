---
name: AWS Directory Service
x-slug: aws-directory-service
description: AWS Directory Service for Microsoft Active Directory (Enterprise Edition),
  also known as AWS Microsoft AD, enables your directory-aware workloads and AWS resources
  to use managed Active Directory in the AWS Cloud. The Microsoft AD service is built
  on actual Microsoft Active Directory and does not require you to synchronize or
  replicate data from your existing Active Directory to the cloud. You can use standard
  Active Directory administration tools and take advantage of built-in Active Directory
  features such as Group Policy, trusts, and single sign-on. With Microsoft AD, you
  can easily joinAmazon EC2andAmazon RDS for SQL Serverinstances to a domain, and
  useAWS Enterprise IT applicationssuch asAmazon WorkSpaceswith Active Directory users
  and groups.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Directory Service
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Directory Service API - Add Ip Routes
  x-api-slug: actionaddiproutes-get
  description: If the DNS server for your on-premises domain uses a publicly addressable
    IP address, you must add a CIDR address block to correctly route traffic to and
    from your Microsoft AD on Amazon Web Services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionaddiproutes-get-openapi.md
- name: AWS Directory Service API - Add Tags To Resource
  x-api-slug: actionaddtagstoresource-get
  description: Adds or overwrites one or more tags for the specified directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionaddtagstoresource-get-openapi.md
- name: AWS Directory Service API - Cancel Schema Extension
  x-api-slug: actioncancelschemaextension-get
  description: Cancels an in-progress schema extension to a Microsoft AD directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncancelschemaextension-get-openapi.md
- name: AWS Directory Service API - Connect Directory
  x-api-slug: actionconnectdirectory-get
  description: Creates an AD Connector to connect to an on-premises directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionconnectdirectory-get-openapi.md
- name: AWS Directory Service API - Create Alias
  x-api-slug: actioncreatealias-get
  description: Creates an alias for a directory and assigns the alias to the directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatealias-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatealias-get-openapi.md
- name: AWS Directory Service API - Create Computer
  x-api-slug: actioncreatecomputer-get
  description: Creates a computer account in the specified directory, and joins the
    computer to the directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatecomputer-get-openapi.md
- name: AWS Directory Service API - Create Conditional Forwarder
  x-api-slug: actioncreateconditionalforwarder-get
  description: Creates a conditional forwarder associated with your AWS directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreateconditionalforwarder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreateconditionalforwarder-get-openapi.md
- name: AWS Directory Service API - Create Directory
  x-api-slug: actioncreatedirectory-get
  description: Creates a Simple AD directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatedirectory-get-openapi.md
- name: AWS Directory Service API - Create Microsoft A D
  x-api-slug: actioncreatemicrosoftad-get
  description: Creates a Microsoft AD in the AWS cloud.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatemicrosoftad-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatemicrosoftad-get-openapi.md
- name: AWS Directory Service API - Create Snapshot
  x-api-slug: actioncreatesnapshot-get
  description: Creates a snapshot of a Simple AD or Microsoft AD directory in the
    AWS cloud.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatesnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatesnapshot-get-openapi.md
- name: AWS Directory Service API - Create Trust
  x-api-slug: actioncreatetrust-get
  description: AWS Directory Service for Microsoft Active Directory allows you to
    configure trust relationships.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatetrust-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actioncreatetrust-get-openapi.md
- name: AWS Directory Service API - Delete Conditional Forwarder
  x-api-slug: actiondeleteconditionalforwarder-get
  description: Deletes a conditional forwarder that has been set up for your AWS directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeleteconditionalforwarder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeleteconditionalforwarder-get-openapi.md
- name: AWS Directory Service API - Delete Directory
  x-api-slug: actiondeletedirectory-get
  description: Deletes an AWS Directory Service directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeletedirectory-get-openapi.md
- name: AWS Directory Service API - Delete Snapshot
  x-api-slug: actiondeletesnapshot-get
  description: Deletes a directory snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeletesnapshot-get-openapi.md
- name: AWS Directory Service API - Delete Trust
  x-api-slug: actiondeletetrust-get
  description: Deletes an existing trust relationship between your Microsoft AD in
    the AWS cloud and an external domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeletetrust-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondeletetrust-get-openapi.md
- name: AWS Directory Service API - Deregister Event Topic
  x-api-slug: actionderegistereventtopic-get
  description: Removes the specified directory as a publisher to the specified SNS
    topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionderegistereventtopic-get-openapi.md
- name: AWS Directory Service API - Describe Conditional Forwarders
  x-api-slug: actiondescribeconditionalforwarders-get
  description: Obtains information about the conditional forwarders for this account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribeconditionalforwarders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribeconditionalforwarders-get-openapi.md
- name: AWS Directory Service API - Describe Directories
  x-api-slug: actiondescribedirectories-get
  description: Obtains information about the directories that belong to this account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribedirectories-get-openapi.md
- name: AWS Directory Service API - Describe Event Topics
  x-api-slug: actiondescribeeventtopics-get
  description: Obtains information about which SNS topics receive status messages
    from the specified directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribeeventtopics-get-openapi.md
- name: AWS Directory Service API - Describe Snapshots
  x-api-slug: actiondescribesnapshots-get
  description: Obtains information about the directory snapshots that belong to this
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribesnapshots-get-openapi.md
- name: AWS Directory Service API - Describe Trusts
  x-api-slug: actiondescribetrusts-get
  description: Obtains information about the trust relationships for this account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribetrusts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondescribetrusts-get-openapi.md
- name: AWS Directory Service API - Disable Radius
  x-api-slug: actiondisableradius-get
  description: Disables multi-factor authentication (MFA) with the Remote Authentication
    Dial In User Service (RADIUS) server for an AD Connector directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondisableradius-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondisableradius-get-openapi.md
- name: AWS Directory Service API - Disable Sso
  x-api-slug: actiondisablesso-get
  description: Disables single-sign on for a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondisablesso-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiondisablesso-get-openapi.md
- name: AWS Directory Service API - Enable Radius
  x-api-slug: actionenableradius-get
  description: Enables multi-factor authentication (MFA) with the Remote Authentication
    Dial In User Service (RADIUS) server for an AD Connector directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionenableradius-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionenableradius-get-openapi.md
- name: AWS Directory Service API - Enable Sso
  x-api-slug: actionenablesso-get
  description: Enables single sign-on for a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionenablesso-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionenablesso-get-openapi.md
- name: AWS Directory Service API - Get Directory Limits
  x-api-slug: actiongetdirectorylimits-get
  description: Obtains directory limit information for the current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiongetdirectorylimits-get-openapi.md
- name: AWS Directory Service API - Get Snapshot Limits
  x-api-slug: actiongetsnapshotlimits-get
  description: Obtains the manual snapshot limits for a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actiongetsnapshotlimits-get-openapi.md
- name: AWS Directory Service API - List Ip Routes
  x-api-slug: actionlistiproutes-get
  description: Lists the address blocks that you have added to a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionlistiproutes-get-openapi.md
- name: AWS Directory Service API - List Schema Extensions
  x-api-slug: actionlistschemaextensions-get
  description: Lists all schema extensions applied to a Microsoft AD Directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionlistschemaextensions-get-openapi.md
- name: AWS Directory Service API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Lists all tags on a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionlisttagsforresource-get-openapi.md
- name: AWS Directory Service API - Register Event Topic
  x-api-slug: actionregistereventtopic-get
  description: Associates a directory with an SNS topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionregistereventtopic-get-openapi.md
- name: AWS Directory Service API - Remove Ip Routes
  x-api-slug: actionremoveiproutes-get
  description: Removes IP address blocks from a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionremoveiproutes-get-openapi.md
- name: AWS Directory Service API - Remove Tags From Resource
  x-api-slug: actionremovetagsfromresource-get
  description: Removes tags from a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionremovetagsfromresource-get-openapi.md
- name: AWS Directory Service API - Restore From Snapshot
  x-api-slug: actionrestorefromsnapshot-get
  description: Restores a directory using an existing directory snapshot.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionrestorefromsnapshot-get-openapi.md
- name: AWS Directory Service API - Start Schema Extension
  x-api-slug: actionstartschemaextension-get
  description: Applies a schema extension to a Microsoft AD directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionstartschemaextension-get-openapi.md
- name: AWS Directory Service API - Update Conditional Forwarder
  x-api-slug: actionupdateconditionalforwarder-get
  description: Updates a conditional forwarder that has been set up for your AWS directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionupdateconditionalforwarder-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionupdateconditionalforwarder-get-openapi.md
- name: AWS Directory Service API - Update Radius
  x-api-slug: actionupdateradius-get
  description: Updates the Remote Authentication Dial In User Service (RADIUS) server
    information for an AD Connector directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionupdateradius-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionupdateradius-get-openapi.md
- name: AWS Directory Service API - Verify Trust
  x-api-slug: actionverifytrust-get
  description: AWS Directory Service for Microsoft Active Directory allows you to
    configure and verify trust relationships.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionverifytrust-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-directory-service/master/_listings/aws-directory-service/actionverifytrust-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.direct.connect.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.directory.service.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/ds/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/directoryservice/latest/devguide/api-ref.html
- type: x-faq
  url: https://aws.amazon.com/directoryservice/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/directoryservice/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/directoryservice/pricing/
- type: x-website
  url: https://aws.amazon.com/directoryservice/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
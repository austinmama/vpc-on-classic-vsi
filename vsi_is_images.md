---

copyright:
  years: 2018, 2019
lastupdated: "2019-05-22"

subcollection: vpc-on-classic-vsi

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:note: .note}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}


# Images
{: #images}

When you provision {{site.data.keyword.vsi_is_full}}, you can select from the supported stock images or a custom image that you've imported from {{site.data.keyword.cos_full_notm}}. The image that you select determines the operating system that is provisioned for your instance. 
{:shortdesc}

## Stock images
{: #stock-images}

The following operating systems are available as stock images when you create a virtual server.
* CentOS 7.x
* Debian 8.x, 9.x
* Red Hat Enterprise Linux 7.x
* Ubuntu 16.04, 18.04
* Windows 2012, 2012 R2, 2016

When you order an instance, the images are cloud-init enabled to optimize provisioning times. With a cloud-init enabled image, you can provide user data. In the **User Data** field on the order form, you can enter optional cloud-init user data for the server. For more information about user data and automation, see [User data](/docs/vpc-on-classic-vsi?topic=vpc-on-classic-vsi-user-data#user-data).

## Virtualization
{: #virtualization}
Instances require an image that supports Hardware Virtualization Machine (HVM) boot mode. The HVM virtualization type allows an image to run directly on a virtual server, which is required for advanced networking and GPU capabilities.
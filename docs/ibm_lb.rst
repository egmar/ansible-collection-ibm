
ibm_lb -- Configure IBM Cloud 'ibm_lb' resource
===============================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_lb' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.0
- Terraform v0.12.20



Parameters
----------

  subnet_id (False, int, None)
    None


  dedicated (False, bool, False)
    None


  ssl_enabled (False, bool, None)
    None


  ssl_offload (False, bool, False)
    None


  hostname (False, str, None)
    None


  security_certificate_id (False, int, None)
    None


  datacenter (False, str, None)
    (Required for new resource)


  ha_enabled (False, bool, False)
    None


  ip_address (False, str, None)
    None


  tags (False, list, None)
    None


  connections (False, int, None)
    (Required for new resource)


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)


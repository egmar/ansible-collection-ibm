
ibm_resource_instance_info -- Retrieve IBM Cloud 'ibm_resource_instance' resource
=================================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Retrieve an IBM Cloud 'ibm_resource_instance' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.0
- Terraform v0.12.20



Parameters
----------

  crn (False, str, None)
    CRN of resource instance


  resource_name (False, str, None)
    The name of the resource


  resource_crn (False, str, None)
    The crn of the resource


  resource_status (False, str, None)
    The status of the resource


  resource_controller_url (False, str, None)
    The URL of the IBM Cloud dashboard that can be used to explore and view details about the resource


  name (True, str, None)
    Resource instance name for example, myobjectstorage


  resource_group_id (False, str, None)
    The id of the resource group in which the instance is present


  status (False, dict, None)
    The resource instance status


  resource_group_name (False, str, None)
    The resource group name in which resource is provisioned


  location (False, str, None)
    The location or the environment in which instance exists


  service (False, str, None)
    The service type of the instance


  plan (False, str, None)
    The plan type of the instance


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)


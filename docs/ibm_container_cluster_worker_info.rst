
ibm_container_cluster_worker_info -- Retrieve IBM Cloud 'ibm_container_cluster_worker' resource
===============================================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Retrieve an IBM Cloud 'ibm_container_cluster_worker' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.0
- Terraform v0.12.20



Parameters
----------

  account_guid (False, str, None)
    The bluemix account guid this cluster belongs to


  region (False, str, None)
    The cluster region


  resource_group_id (False, str, None)
    ID of the resource group.


  status (False, str, None)
    Status of the worker


  public_vlan (False, str, None)
    None


  space_guid (False, str, None)
    The bluemix space guid this cluster belongs to


  private_ip (False, str, None)
    None


  public_ip (False, str, None)
    None


  org_guid (False, str, None)
    The bluemix organization guid this cluster belongs to


  resource_controller_url (False, str, None)
    The URL of the IBM Cloud dashboard that can be used to explore and view details about this cluster


  worker_id (True, str, None)
    ID of the worker


  state (False, str, None)
    State of the worker


  private_vlan (False, str, None)
    None


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)


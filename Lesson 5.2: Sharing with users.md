# 5.2: Sharing with users

In this lesson, you’ll learn how you can use roles, permissions, and spaces to share dashboards with others.

In this lab, you will create a user with limited access to view a shared Dashboard

  Elastic Security uses Role-Based Access Control (RBAC). Whenever you need to give out permissions to view an asset, start with the Role. Manage these settings by clicking on:
  > Stack Management > Security > Roles

  ## a) Elasticsearch
    Role Name: dashviewer
    Indices: kibana_sample_data_logs
    Privileges: read, view_index_metadata

  ## b) Kibana
    Spaces: Nova
    Privileges for all features:  Customize (Dashboard: Read)

  > Stack Management > Security > Users

  ## a) Create User
    Username: public
    Full Name: Tadeu Augusto Dutra Pinto
    Password: public123
    Privileges > Roles: dashviewer


<img width="1917" height="950" alt="image" src="https://github.com/user-attachments/assets/d1fe3b0a-70ad-4551-9034-111bd5669889" />


# Summary

In this lab, you shared a Dashboard with a user with limited access.
  
# Review

- Roles are a collection of privileges that allow you to perform actions in Kibana and Elasticsearch.
- Roles provides authorization to specific actions.
- Anonymous authentication will provide access to all of Kibana, so restrict the privileges of the anonymous user.
- Users can be assigned a role that only provides access to spaces that have limited features enabled.
- You can use roles to limit the spaces that users with those roles have access to. Those spaces can then be configured with a limited set of features.

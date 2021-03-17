# Additional Clusterroles 
that are required for developers to work with sealed secrets:
- Usage:
  ```
  oc apply -f clusterroles.yaml

  oc policy add-cluster-role-to-user sealed-secrets-editor alice -n   <NAMESPACE>
  
  oc policy add-cluster-role-to-user sealed-secrets-viewer bob   -n   <NAMESPACE>
  ```


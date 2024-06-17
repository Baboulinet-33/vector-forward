Roles:

oc adm policy add-scc-to-user privileged -n infra-test-fw -z vector

oc adm policy add-cluster-role-to-user metadata-reader -z vector -n infra-test-fw
# Automatic Kubernetes ETCD Backup

The repository covers an automatic procedure for backing up an etcd cluster in Kubernetes / OpenShift environments.

To apply the automatic backup process run the next commands -

```
$ git clone https://github.com/michaelkotelnikov/auto-etcdbackup.git

$ kubectl apply -k ./auto-etcdbackup
```

The commands will initialize a recursive etcd backup process. The database will be backed up once a week.
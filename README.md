# akto-poc1

#root@MSBR-GPU-1:~/akto-testing# kubectl get svc
#NAME             TYPE           CLUSTER-IP     EXTERNAL-IP      PORT(S)          AGE
#akto-dashboard   LoadBalancer   10.0.69.64     20.247.212.147   8080:31493/TCP   4m38s
#akto-keel        LoadBalancer   10.0.55.240    20.247.212.121   9300:31821/TCP   4m38s
#akto-runtime     ClusterIP      10.0.161.15    <none>           9092/TCP         4m38s
#mongo-lb         ClusterIP      10.0.224.243   <none>           27017/TCP        5h41m
#root@MSBR-GPU-1:~/akto-testing#
#
#
#root@MSBR-GPU-1:~/akto-testing# kubectl get pod
#NAME                            READY   STATUS    RESTARTS   AGE
#akto-dashboard-df7bfc7f-7jjt4   2/2     Running   0          5m43s
#akto-keel-5d4c44b7d8-h74g8      1/1     Running   0          7m3s
#akto-runtime-74dc697df-hkr9j    3/3     Running   0          3m2s
#akto-runtime-74dc697df-zpq67    3/3     Running   0          4m6s
#akto-testing-6bcd86b454-8hlgf   2/2     Running   0          3m9s
#mongodb-replica-0               1/1     Running   0          5h54m
#mongodb-replica-1               1/1     Running   0          5h48m
#root@MSBR-GPU-1:~/akto-testing#

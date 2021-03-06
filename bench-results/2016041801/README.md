

- Google Cloud Compute Engine
- 8 vCPUs + 16GB Memory + 50GB SSD
- 1 machine(client) of 16 vCPUs + 30GB Memory + 50GB SSD
- Ubuntu 15.10
- Go 1.6, 1.7
- Java 8
  - Java(TM) SE Runtime Environment (build 1.8.0_74-b02)
  - Java HotSpot(TM) 64-Bit Server VM (build 25.74-b02, mixed mode)
- Consul v0.6.4
- etcd v3 (master branch)
- Zookeeper v3.4.8



<br><br><hr>
##### Write 200K keys, 1000-client, 8-byte key, 256-byte value (etcd v2)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/01-avg-latency-ms.svg" alt="2016041801/01-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/01-throughput.svg" alt="2016041801/01-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/01-avg-cpu.svg" alt="2016041801/01-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/01-avg-memory.svg" alt="2016041801/01-avg-memory">



<br><br><hr>
##### Write 500K keys, 1-client, 8-byte key, 256-byte value (etcd v2)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/02-avg-latency-ms.svg" alt="2016041801/02-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/02-throughput.svg" alt="2016041801/02-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/02-avg-cpu.svg" alt="2016041801/02-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/02-avg-memory.svg" alt="2016041801/02-avg-memory">



<br><br><hr>
##### Write 500K keys, 1000-client, 8-byte key, 256-byte value (etcd v2)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/03-avg-latency-ms.svg" alt="2016041801/03-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/03-throughput.svg" alt="2016041801/03-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/03-avg-cpu.svg" alt="2016041801/03-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/03-avg-memory.svg" alt="2016041801/03-avg-memory">



<br><br><hr>
##### Write 1M keys, 1000-client, 8-byte key, 256-byte value (etcd v2, Test 1)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/04-avg-latency-ms.svg" alt="2016041801/04-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/04-throughput.svg" alt="2016041801/04-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/04-avg-cpu.svg" alt="2016041801/04-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/04-avg-memory.svg" alt="2016041801/04-avg-memory">



<br><br><hr>
##### Write 1M keys, 1000-client, 8-byte key, 256-byte value (etcd v2, Test 2)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/05-avg-latency-ms.svg" alt="2016041801/05-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/05-throughput.svg" alt="2016041801/05-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/05-avg-cpu.svg" alt="2016041801/05-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/05-avg-memory.svg" alt="2016041801/05-avg-memory">



<br><br><hr>
##### Write 200K keys, 1000-client, 8-byte key, 256-byte value (Consul v0.6.4)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/06-avg-latency-ms.svg" alt="2016041801/06-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/06-throughput.svg" alt="2016041801/06-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/06-avg-cpu.svg" alt="2016041801/06-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/06-avg-memory.svg" alt="2016041801/06-avg-memory">



<br><br><hr>
##### Write 500K keys, 1-client, 8-byte key, 256-byte value (Consul v0.6.4)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/07-avg-latency-ms.svg" alt="2016041801/07-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/07-throughput.svg" alt="2016041801/07-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/07-avg-cpu.svg" alt="2016041801/07-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/07-avg-memory.svg" alt="2016041801/07-avg-memory">



<br><br><hr>
##### Write 500K keys, 1000-client, 8-byte key, 256-byte value (Consul v0.6.4)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/08-avg-latency-ms.svg" alt="2016041801/08-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/08-throughput.svg" alt="2016041801/08-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/08-avg-cpu.svg" alt="2016041801/08-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/08-avg-memory.svg" alt="2016041801/08-avg-memory">



<br><br><hr>
##### Write 1M keys, 1000-client, 8-byte key, 256-byte value (Consul v0.6.4, Test 1)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/09-avg-latency-ms.svg" alt="2016041801/09-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/09-throughput.svg" alt="2016041801/09-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/09-avg-cpu.svg" alt="2016041801/09-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/09-avg-memory.svg" alt="2016041801/09-avg-memory">



<br><br><hr>
##### Write 1M keys, 1000-client, 8-byte key, 256-byte value (Consul v0.6.4, Test 2)

<img src="https://storage.googleapis.com/dbtester-results/2016041801/10-avg-latency-ms.svg" alt="2016041801/10-avg-latency-ms">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/10-throughput.svg" alt="2016041801/10-throughput">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/10-avg-cpu.svg" alt="2016041801/10-avg-cpu">

<img src="https://storage.googleapis.com/dbtester-results/2016041801/10-avg-memory.svg" alt="2016041801/10-avg-memory">




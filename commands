# GCP VPC Peering Commands

## Set Project

```bash
gcloud config set project PROJECT_ID
```

---

## Create Network A

```bash
gcloud compute networks create network-a \
--subnet-mode custom
```

---

## Create Subnet

```bash
gcloud compute networks subnets create network-a-central \
--network network-a \
--range 10.0.0.0/16 \
--region us-central1
```

---

## Create VM

```bash
gcloud compute instances create vm-a \
--zone us-central1-a \
--network network-a \
--subnet network-a-central
```

---

## Firewall Rule

```bash
gcloud compute firewall-rules create network-a-fw \
--network network-a \
--allow tcp:22,icmp
```

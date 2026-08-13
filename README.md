# ☸️ CKA Preparation

This repository documents my ongoing **Certified Kubernetes Administrator (CKA)** preparation through structured, hands-on Kubernetes labs.

The focus is on developing practical Kubernetes administration, troubleshooting, and exam-oriented problem-solving skills rather than only studying theory.

---

## 🎯 Preparation Approach

```text
Kubernetes Fundamentals
        ↓
CKA-focused Hands-on Practice
        ↓
Exam-oriented Scenarios
        ↓
Troubleshooting
        ↓
CKA Certification
```

Kubernetes fundamentals and broader learning are maintained separately in the **Kubernetes Fundamentals & Hands-on Labs** repository.

---

# 🟢 Part A — Pods — COMPLETE

Hands-on CKA-focused Pod preparation completed.

### Pod Fundamentals

* Pod creation
* Pod YAML
* YAML structure and anatomy
* Pod specifications
* Pod lifecycle
* Pod phases

  * Pending
  * Running
  * Succeeded
  * Failed
  * Unknown
* Container states

  * Waiting
  * Running
  * Terminated
* RestartPolicy
* Exit codes
* Pod deletion and recreation
* Editing existing Pods
* Immutable Pod fields

### Container & Pod Configuration

* Environment variables
* Container commands and arguments
* Multi-container Pods
* Init Containers
* Container logs
* `kubectl exec`
* Selecting and filtering Pods
* Working with Pods across namespaces

### Pod Troubleshooting

Practiced scenarios involving:

* CrashLoopBackOff
* ImagePullBackOff
* ErrImagePull
* Pending Pods
* ContainerCreating
* Container termination
* Incorrect commands / arguments
* Image availability problems
* Scheduling failures
* Insufficient CPU
* Untolerated taints
* Pod events
* Resource requests and limits
* OOMKilled
* CPU throttling vs memory limits
* Graceful container termination
* SIGTERM → SIGKILL
* Immutable Pod fields

### CKA Pod Practice

Practiced solving Pod scenarios using:

```bash
kubectl get
kubectl describe
kubectl logs
kubectl exec
kubectl edit
kubectl delete
kubectl get -o yaml
kubectl get -o jsonpath
```

The objective was to become comfortable with **reading a question, identifying the Kubernetes concept involved, choosing the correct command, making the required change, and validating the result.**

---

# 🟡 Part B — Deployments — IN PROGRESS

Currently preparing the Deployment section with CKA-focused hands-on practice.

### Topics

* Deployment creation
* Deployment YAML
* Deployment → ReplicaSet → Pod relationship
* Replicas
* Scaling
* Labels
* Selectors
* Rollout
* Rolling updates
* Rollback
* Revision history
* Deployment troubleshooting
* CKA-style Deployment scenarios

---

## 🧪 Hands-on Practice

CKA preparation is performed through practical Kubernetes environments and command-line labs.

Practice includes:

* Creating resources from YAML
* Modifying manifests
* Running `kubectl` commands
* Intentionally creating failures
* Troubleshooting failures
* Deleting and recreating resources
* Validating Kubernetes behaviour
* Solving exam-style scenarios under time constraints

---

## 📁 Repository Structure

CKA preparation materials are organized by topic.

```text
cka-preparation/
│
├── README.md
│
├── part-a-pods/
│   ├── YAML manifests
│   └── practice materials
│
├── part-b-deployments/
│   ├── YAML manifests
│   └── practice materials
│
└── future CKA sections...
```

Only useful and reusable practice manifests will be added to this repository rather than every temporary YAML created during experimentation.

---

## 📈 Current Progress

| CKA Section          | Status         |
| -------------------- | -------------- |
| Part A — Pods        | 🟢 Complete    |
| Part B — Deployments | 🟡 In Progress |
| Services             | ⚪ Pending      |
| Networking           | ⚪ Pending      |
| Storage              | ⚪ Pending      |
| Configuration        | ⚪ Pending      |
| Security             | ⚪ Pending      |
| Scheduling           | ⚪ Pending      |
| Troubleshooting      | ⚪ Pending      |
| Other CKA Topics     | ⚪ Pending      |

---

## 🧠 Preparation Philosophy

The goal is not simply to memorize Kubernetes commands.

For every topic, the preparation focuses on:

```text
Understand
   ↓
Practice
   ↓
Break
   ↓
Troubleshoot
   ↓
Fix
   ↓
Validate
   ↓
Repeat
```

This repository will continue to evolve as the CKA preparation progresses.

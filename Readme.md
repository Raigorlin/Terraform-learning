# My learning steps of Terraform

## 為何要學Terraform? 
---
雲端化越來越普及以及伺服器管理以及規模越來越龐大, 如果繼續使用手動或腳本的的形式已經成為不是最理想的解決方式, 因此衍生出利用代碼來進行硬體機器的管理. 那為什麼不用Ansible 等方式部署呢? 原因是Ansible 也有很強的部署能力, 但由於他的架構比較適合部署系統裡面的軟體, 而比較不適合部署硬體相關的架構. 有什麼好處呢?

1. 利用雲端廠商所提供的API來進行自動部署減少人為失誤
2. 可以將所有的設定放在同一個TF 檔案裡


## 學習步驟
---
**Table *of* Contents**

1. [如何開始](#如和開始)

### 如何開始
---

1. [安裝Terraform](#https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli#install-terraform) 
2. [安裝 AWS 指令](#https://aws.amazon.com/tw/cli/)
3. [設定 AWS IAM 權限](#設定-aws-iam-權限)
4. 

#### 設定 AWS IAM 權限
---

- 移動到IAM/使用者群組
- ![alt text](aws-iam-setup.png)
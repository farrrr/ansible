# ansible

1. 在 inventory 目錄下創建你所要管理的機器群分類，例如 Company1, Company2
2. 在目錄下建立該集群的 ansible.cfg / hosts 檔案，視情況建立 group_vars / host_vars 目錄。
3. 執行 playbook `ansible-playbook ../../playbooks/what-you-need-to-do.yml` 即可。

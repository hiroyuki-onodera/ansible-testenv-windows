
# Windows上でDockerを使用したKitchenCI環境を作成する

Windows上のDocker環境Aから、別のDocker環境Bを起動してansible playbookを適用させるKitchenCI環境を構築する



## 環境

- Windows10 Pro: 1909
- Docker Desktop on Windows: Docker version 19.03.5, build 633a0ea
- Chef Workstation: 0.11.21
- git for windows: git version 2.25.1.windows.1

## 前提

- Docker for windowsを設定済み
ｰ Gitを設定済み
- Chef Workstationを導入してGit bash環境における~/.bash_profileに必要設定済み

  ~/.bash_profileに以下を追加など
  eval "$( /c/opscode/chef-workstation/bin/chef shell-init bash | sed -e 's|C:|/c|g'  -e 's|\\|/|g'  -e 's|;|:|g' )"

## gitを設定

```
$

```

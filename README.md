# Ansibele Learn The Easy Way

## 1. What is Ansible !

![Image ](https://github.com/NileshChandekar/ansible_learn_the_easy_way/blob/master/images/a1.png)

#### Change Management

  * Define a System State
  * Enforce the system State
  * Example :

    * Apache web installed
    * Apache web at version xxx
    * Apache web started.

#### Provisioning

  * Prepare a system to make it ready
  * transition of system from one state to different state.
  * Example :

    * Make an FTP server
    * Make an Apache server
    * Make an NFS server.

![Image ](https://github.com/NileshChandekar/ansible_learn_the_easy_way/blob/master/images//a2.png)

#### Automation

  * Define task to be executed automatically.
  * It has ordered task
  * It can make decision
  * It can run Ad-hoc task.

#### Orchestration

  * Can be used to orchastrate so many systems
  * Coordinates automation between the systems.

![Image ](https://github.com/NileshChandekar/ansible_learn_the_easy_way/blob/master/images//a2.png)


#### Why Ansible???

  * Its clean...!
  * Fast.
  * No agent. i.e. Agentless
  * No DB. easy to move from one system to other easialy.
  * No residual software. no footprints on remote system.
  * No complex upgrades.
  * Easy to extend
  * Shell commands.
  * Script.
  * URL/Restfull calls.
  * Ansible-Galaxy.

#### YAML

  * It uses YAML to create your task.
  * No programing required
  * NOT a markup language
  * Structured language, writting
  * Easy to read and write.

#### Secure

  * Build in security
  * Uses SSH.
  * Root/Sudo usage.
  * Encrupted vault.
  * No PKI needed.

## 2. Architecture and Process Flow.

  * There are two parts in topology.
    * Ansible Control Server
    * Remote Server

#### Requirement

  * Control Server:
    * Python 2.6+
    * Must be *NIX (Linux/Unix/Mac)*
    * Windows not support, it can be workable with lot of tweeks.

  * Control Server:
    * *Nix: Python 2.4 (simplejson)*
    * *Nix: Python 2.5*
    * SSH
    * *Windows: Remote Powershell Enabled*

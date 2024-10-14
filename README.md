# VirtualBox ACPI Shutdown Guide

Ce guide explique comment utiliser la commande `VBoxManage` pour effectuer un arrêt ACPI (simulation du bouton d'alimentation) sur une machine virtuelle dans **VirtualBox**.

## Prérequis

- VirtualBox doit être installé sur votre machine hôte (Windows, macOS, ou Linux).
- Assurez-vous que **VBoxManage** est accessible depuis la ligne de commande.

## Étapes à suivre

### 1. Localiser `VBoxManage`

L'outil **VBoxManage** est inclus avec l'installation de VirtualBox. Par défaut, il est situé dans le répertoire d'installation de VirtualBox.

- Sous **Windows**, le chemin est généralement :
  ```bash
  C:\Program Files\Oracle\VirtualBox\

### 2. Executer la commande
 ```bash 
    VBoxManage controlvm "NomDeLaVM" acpipowerbutton

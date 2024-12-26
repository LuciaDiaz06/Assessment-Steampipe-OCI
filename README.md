# Assessment Steampipe-OCI
Steampipe es un motor de código abierto que permite consultar las API de la nube mediante SQL. OCI, por su parte, es una nube de Oracle que permite ejecutar aplicaciones de forma más rápida y segura

# Requisitos

1. Crear Maquina Virtual OCI - Se recomienda este en Linux 9. Se puede descargar para otros S.O pero para este ejercicio se utilizara Linux 9
2. Actualizar la máquina virtual
3. Tener permisos de usuario administrador en el Tenant de OCI

# Documentación

https://hub.steampipe.io/

# Instalación

1. Actualizar la instancia
```
sudo dnf update -y

```

https://docs.oracle.com/es-ww/iaas/Content/API/SDKDocs/cliinstall.htm#InstallingCLI__oraclelinux9

2. Instalar CLI en la instnacia

```
sudo dnf -y install oraclelinux-developer-release-el9
sudo dnf install python39-oci-cli
```

3. Preparar la instancia de OCI para luego instalar el Steampipe
4. Validar versión OCI

```
oci setup config
```
5. Se pedira el OCID Tenancy y el OCID Usuario



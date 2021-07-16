# Heading 1

CORTX is a distributed object storage system designed for great efficiency, massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

1. CORTX is a distributed object storage system designed for great efficiency
2. massive capacity, and high HDD-utilization. CORTX is 100% Open Source.
3. Most of the project is licensed under the Apache 2.0 License and the rest

    - is under AGPLv3; check the specific License file for each submodule to
    - determine which is which.
      - ghtikskghd


4. CORTX is a *distributed* **object** ***storage*** _system_ __designed__ ___for___ great efficiency, `yum install git -y`

    ```
        yum install -y yum-utils
        yum-config-manager --add-repo "${CORTX_RELEASE_REPO}/3rd_party/"
        yum-config-manager --add-repo "${CORTX_RELEASE_REPO}/cortx_iso/"

        cat <<EOF >/etc/pip.conf
        [global]
        timeout: 60
        index-url: $CORTX_RELEASE_REPO/python_deps/
        trusted-host: $(echo $CORTX_RELEASE_REPO | awk -F '/' '{print $3}')
        EOF

        # Cortx Pre-requisites
        yum install --nogpgcheck -y java-1.8.0-openjdk-headless
        yum install --nogpgcheck -y python3 cortx-prereq sshpass

        # Pre-reqs for Provisioner
        yum install --nogpgcheck -y python36-m2crypto salt salt-master salt-minion

        # Provisioner API
        yum install --nogpgcheck -y python36-cortx-prvsnr

        # Verify provisioner version (0.36.0 and above)
        provisioner --version
    ```


For more information, see [H2](#H2).

For more information, see [Google](https://github.com/Seagate/cortx/blob/main/doc/community-build/ProvisionReleaseBuild.md).

For more information, see https://github.com/Seagate/cortx/blob/main/doc/community-build/ProvisionReleaseBuild.md.


## H2

CORTX is a distributed object storage system designed for great efficiency, massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

- CORTX is a distributed object storage system designed for great efficiency,
- massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most
- of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

### H3

CORTX is a distributed object storage system designed for great efficiency, massive capacity, and high HDD-utilization. CORTX is 100% Open Source. Most of the project is licensed under the Apache 2.0 License and the rest is under AGPLv3; check the specific License file for each submodule to determine which is which.

- [X] CORTX Follows
- [ ] Core
- [ ] more

#### H4

###### H5

###### H6

| Header | Header |
|--------|--------|
| Header | Header |
| Header | Header |
| Header | Header |
| Header | Header |

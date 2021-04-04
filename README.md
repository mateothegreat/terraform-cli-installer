# Install or upgrade terraform cli

## One-liner

```bash
wget https://raw.githubusercontent.com/mateothegreat/terraform-cli-installer/main/tf-install && \
chmod +x tf-install && \
./tf-install
```

## Running

```bash
./tf-upgrade [optional output dir like /usr/local/bin]
```

## Example output

```bash
(venv) ➜  a git:(main) ✗ wget https://raw.githubusercontent.com/mateothegreat/terraform-cli-installer/main/tf-install && \
chmod +x tf-install && \
sudo ./tf-install

--2021-04-04 04:16:21--  https://raw.githubusercontent.com/mateothegreat/terraform-cli-installer/main/tf-install
Resolving raw.githubusercontent.com (raw.githubusercontent.com)... 185.199.108.133, 185.199.109.133, 185.199.110.133, ...
Connecting to raw.githubusercontent.com (raw.githubusercontent.com)|185.199.108.133|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1092 (1.1K) [text/plain]
Saving to: ‘tf-install’

tf-install                                                                          100%[=================================================================================================================================================================================================================>]   1.07K  --.-KB/s    in 0s      

2021-04-04 04:16:22 (27.4 MB/s) - ‘tf-install’ saved [1092/1092]

Installing Terraform 0.14.9 on darwin (amd64) in to /usr/local/bin..
--2021-04-04 04:16:22--  https://releases.hashicorp.com/terraform/0.14.9/terraform_0.14.9_darwin_amd64.zip
Resolving releases.hashicorp.com (releases.hashicorp.com)... 2a04:4e42:30::439, 199.232.33.183
Connecting to releases.hashicorp.com (releases.hashicorp.com)|2a04:4e42:30::439|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34593800 (33M) [application/zip]
Saving to: ‘terraform_0.14.9_darwin_amd64.zip’

terraform_0.14.9_darwin_amd64.zip                                                   100%[=================================================================================================================================================================================================================>]  32.99M  13.2MB/s    in 2.5s    

2021-04-04 04:16:25 (13.2 MB/s) - ‘terraform_0.14.9_darwin_amd64.zip’ saved [34593800/34593800]

Archive:  terraform_0.14.9_darwin_amd64.zip
  inflating: /usr/local/bin/terraform  
Terraform 0.14.9 installed to /usr/local/bin/terraform.
```

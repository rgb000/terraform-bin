# Python wrapper for Terraform binary

This is a Python wrapper for Hashicorp's Terraform. Using `terraform-bin` you can install Terraform using Pipenv or Pip, instead of manually downloading, unzipping and installing it.

## Usage

```sh
pipenv install --dev terraform-bin

terraform init # Now you can use terraform, after you installed it with Pipenv or Pip.
```

## Build wheel

Windows:

```sh
build-wheel.bat
```

Linux/Mac:

```sh
build-wheel.sh
```

## License

This project is [Apache License Version 2.0](LICENSE).

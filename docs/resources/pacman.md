## pacman

The `pacman` resource is used for package management on Arch Linux
systems.

## Parameters

### name

Name of the package.

* Type: string
* Required: Yes
* Default: Defaults to the resource title

### state

Desired state of the package.

* Type: string
* Required: No
* Default: present

## Example usage

```hcl
pacman "tmux" {
  state = "present"
}
```
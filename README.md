<img
  src="https://raw.githubusercontent.com/42Lyon-an22mo07-piscinec/vscode-42header/master/42.png"
  width=128>

# 42 Header for VSCode

This extension provides the 42 header integration in VS Code.

```bash
# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    vscode-42header                                    :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: kube <hello@kube.io>                       +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2013/11/18 13:37:42 by kube              #+#    #+#              #
#    Updated: 2016/09/18 13:11:04 by kube             ###   ########lyon.fr    #
#                                                                              #
# **************************************************************************** #
```

## Install

```
git clone https://github.com/42Lyon-an22mo07-piscinec/vscode-42header
cp -r vscode-42header .vscode/extensions/
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "42header.username": string,
  "42header.email": string
}
```


## Issues

In case of a bug, or missing feature, please create a [Github Pull Request](https://github.com/42Lyon-an22mo07-piscinec/vscode-42header/pulls).

## License

MIT

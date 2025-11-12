# duotail-helm-charts
Helm charts for duotail project

## Postfix
### Networking Options
| Key         | Type    | Default         | Description                        |
|-------------|---------|-----------------|------------------------------------|
| hostNetwork | bool    | `false`         | Enable host networking             |
| dnsPolicy   | string  | `ClusterFirst`  | Set DNS policy for the pod         |

### Release Notes
- **~~0.1.2~~**: _**Spoiled image release**_
- **0.1.3**: Enable sasl authentication for postfix
- **~~0.1.4~~**: _**Spoiled image release**_

## Manager

### Release Notes
- **0.1.0**: latest release
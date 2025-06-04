# duotail-helm-charts
Helm chart for duotail project

## Postfix
### Networking Options
| Key         | Type    | Default         | Description                        |
|-------------|---------|-----------------|------------------------------------|
| hostNetwork | bool    | `false`         | Enable host networking             |
| dnsPolicy   | string  | `ClusterFirst`  | Set DNS policy for the pod         |

### Release Notes
- **~~0.1.2~~**: _**Spoiled image release**_
- **0.1.3**: Enable sasl authentication for postfix
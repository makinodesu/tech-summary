| No  |      First      |     Second      |  Third(only x)  |
| :-: | :-------------: | :-------------: | :-------------: |
|  1  | <li>- [ ] </li> | <li>- [x] </li> | <li>- [x] </li> |
|  2  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  3  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  4  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  5  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  6  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  7  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  8  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
|  9  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 10  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 11  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 12  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 13  | <li>- [ ] </li> | <li>- [x] </li> | <li>- [x] </li> |
| 14  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 15  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 16  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 17  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 18  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 19  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 20  | <li>- [ ] </li> | <li>- [x] </li> | <li>- [ ] </li> |
| 21  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 22  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 23  | <li>- [ ] </li> | <li>- [ ] </li> | <li>- [ ] </li> |
| 24  | <li>- [ ] </li> | <li>- [x] </li> | <li>- [x] </li> |
| 25  | <li>- [ ] </li> | <li>- [x] </li> | <li>- [x] </li> |

# 7

- DHCP relay

```mermaid
sequenceDiagram
    DHCP Client->>Router: Broadcast
    Router->>DHCP Server: Unicast
    DHCP Server->>Router: Response
    Router->>DHCP Client: Response
```

# 3

Confirm:IGPの更新トリガー

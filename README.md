# netadmin-cisco-topologies

Топологии и конфиги Cisco IOS для лаб (совместимо с Packet Tracer / GNS3 — импортируйте конфиги вручную).

## Топология 1
```
[PC1]--[SW1]--[R1]--[R2]--[SW2]--[PC2]
```
См. `configs/router1.cfg`, `configs/router2.cfg`, `configs/switch1.cfg`.

## Топология 2 и 3
- [`topologies/topology2.md`](topologies/topology2.md) — статическая маршрутизация через транзитный маршрутизатор (`configs/topology2/`).
- [`topologies/topology3.md`](topologies/topology3.md) — резервирование шлюза HSRP с отслеживанием uplink (`configs/topology3/`).
- [`docs/ip-plan.md`](docs/ip-plan.md) — единый план адресации; [`docs/verification.md`](docs/verification.md) — проверка топологий.

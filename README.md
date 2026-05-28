## SNI Configs (اگه نمی دونید چطوری ترکیب کنید، جدول های بعدی برای شماست)

> If you don't know what SNI-Spoofing configurations are for, skip this table.

> https://t.me/DeltaSNI برای آموزش و گفت و گو درباره روش های مبتنی بر این روش در گروه تلگرامی ما عضو بشید

> لطفا هر پروژه ای براتون مفید بود حتما استار بدید، با این کار انگیزه توسعه دهنده برای ادامه رو تامین می کنید🫀

| Type | Count | Link |
|---|---|---|
| All SNI configs | — | [all_configs_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/all_configs_sni.txt) |
| Protocol: VLESS | 147 | [vless_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/vless_sni.txt) |
| Protocol: VMESS | 39 | [vmess_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/vmess_sni.txt) |
| Protocol: SS | 101 | [ss_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/ss_sni.txt) |
| Protocol: TROJAN | 31 | [trojan_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/trojan_sni.txt) |
| Batch 001 | 318 | [batch_001.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/sni_v2ray/batch_001.txt) |

---

## Main Files

### V2ray — All Configs

| File | Link |
|---|---|
| All configs (txt) | [all_configs.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/all_configs.txt) |

### V2ray — By Protocol

| Protocol | Count | Link |
|---|---|---|
| VLESS | 147 | [vless.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vless.txt) |
| VMESS | 39 | [vmess.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vmess.txt) |
| SS | 101 | [ss.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/ss.txt) |
| TROJAN | 31 | [trojan.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/trojan.txt) |

### Clash 

Groups: **PROXY** (selector) → **Load-Balance** · **Auto** · **Fallback**

| File | Link |
|---|---|
| clash.yaml (all protocols) | [clash.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/clash.yaml) |
| vless_clash.yaml | [vless_clash.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vless_clash.yaml) |
| vmess_clash.yaml | [vmess_clash.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vmess_clash.yaml) |
| ss_clash.yaml | [ss_clash.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/ss_clash.yaml) |
| trojan_clash.yaml | [trojan_clash.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/trojan_clash.yaml) |

---

## Batch Files — Random 500-Config Groups

> Each file contains 500 randomly selected configs from all protocols.

### V2ray Batches

| Batch | Count | Link |
|---|---|---|
| Batch 001 | 318 | [batch_001.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/v2ray/batch_001.txt) |

### Clash Batches

| Batch | Link |
|---|---|
| Batch 001 | [batch_001.yaml](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/clash/batch_001.yaml) |

---

## Statistics

### Per-Protocol Input & Output

| Protocol | Tested (unique) | valid | Pass Rate |
|---|---|---|---|
| VLESS | 2165 | 147 | 6.8% |
| VMESS | 423 | 39 | 9.2% |
| SS | 311 | 101 | 32.5% |
| TROJAN | 210 | 31 | 14.8% |
| SSR | 8 | 0 | 0.0% |
| HY2 | 0 | 0 | 0.0% |
| HY | 0 | 0 | 0.0% |
| TUIC | 1 | 0 | 0.0% |
| **Total** | **3118** | **318** | **10.2%** |

| Metric | Value |
|---|---|
| Raw fetched lines | 4644 |
| Unique after dedup | 3118 |
| Valid configs | 318 |
| Processing time | 267.79s |

---

## 🔥 Keep This Project Going!

If you're finding this useful, please show your support:

⭐ **Star the repository on GitHub**

⭐ **Star our [Telegram posts](https://t.me/DeltaKroneckerGithub)** 

Your stars fuel our motivation to keep improving!

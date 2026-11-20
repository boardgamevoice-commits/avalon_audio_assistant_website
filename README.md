# Board Game Audio Assistant Official Website (`Avalon_audio_asasistant_website`)

> **绑定 iOS 应用**：Board Game Audio Assistant (`6755318411` / `com.devfang.AvalonAudioAssistant`)
> **Synchronized App Version**: `v1.3.0` (Build `18`)
> **本地客户端源码**：[`../Avalon_Audio_Assistant`](../Avalon_Audio_Assistant)
> **Netlify 站点名称**：`boardgameaudioassistant` (`ed420010-72bc-453f-8a02-5b1d2219214b`)
> **生产环境域名**：https://boardgameaudioassistant.netlify.app/
> **隐私政策地址**：https://boardgameaudioassistant.netlify.app/privacy
> **服务条款地址**：https://boardgameaudioassistant.netlify.app/terms
> **GitHub 远端仓库**：`https://github.com/boardgamevoice-commits/avalon_audio_assistant_website.git`

---

## 文件结构

- `index.html` / `index.css`：官方响应式双语落地页与交互式演示（同步支持 7 大桌游、面对面局域网秘密发牌、阿瓦隆贝叶斯概率推演与 iPhone Duo / iPad 多任务适配）
- `privacy.html`：中英双语隐私政策（本地沙盒、麦克风、局域网 Bonjour、StoreKit 2 内购及 Google AdMob / UMP / ATT 合规声明）
- `terms.html`：中英双语使用条款与免责声明（含 StoreKit 2 终身免广告买断、家人共享与恢复购买条款）
- `app-ads.txt`：Google AdMob 授权数字卖家验证文件
- `netlify.toml`：Clean URL 重定向（`/privacy`、`/terms`）与安全响应头配置
- `assets/`：高清 1024x1024 应用图标与视觉素材

## 部署与验证命令

```bash
python3 /Users/devfang/.gemini/config/skills/ios-app-store-publisher/scripts/sync_and_verify_website.py \
    --project-dir ../Avalon_Audio_Assistant \
    --deploy --strict
```

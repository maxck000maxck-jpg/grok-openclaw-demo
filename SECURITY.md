# 🛡️ Security Policy

**Grok + OpenClaw Demo**

**Status**: ✅ Clean audit (0 critical, 0 warn)

**Trust Model**: Personal assistant (single trusted user)

### Hardening Commands
```bash
openclaw config set gateway.mode local
openclaw doctor --generate-gateway-token
openclaw gateway restart
openclaw security audit --deep
openclaw exec-policy preset cautious

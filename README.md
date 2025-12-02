# pihole-blocklist-brasil
Lista brasileira de bloqueio para Pi-hole, focada em anúncios, rastreadores e domínios invasivos usados principalmente no Brasil.
# 🇧🇷 Pi-hole Blocklist Brasil

Lista brasileira de bloqueio para **Pi-hole**, focada em anúncios, rastreadores e domínios invasivos usados principalmente no Brasil.

Esta lista foi criada para complementar as blocklists internacionais tradicionais, trazendo filtros específicos para:

* Plataformas brasileiras de anúncios
* Adservers nacionais
* Sites de rastreamento usados por apps e serviços locais
* Domínios de telemetria e coleta abusiva
* Serviços de redirecionamento e click-tracking comuns no Brasil

Ideal para quem quer deixar o Pi-hole mais eficiente no cenário brasileiro.

---

## 📌 Objetivo da lista

O foco é ser:

* **Leve** – sem milhares de domínios desnecessários
* **Específica** – voltada ao tráfego brasileiro
* **Compatível** – 100% funcional no Pi-hole, AdGuard Home e outros DNS sinkholes
* **Atualizada** – domínios adicionados com base em uso real

---

## 📥 Instalação

### **1. Abra o painel do Pi-hole**

```
http://pi.hole/admin
```

### **2. Vá em:**

**Group Management → Adlists → Add a new adlist**

### **3. Adicione a URL da lista:**

```
https://raw.githubusercontent.com/kevinaugusto0/pihole-blocklist-brasil/main/blocklist.txt
```

### **4. Atualize as Gravity Rules**

```bash
pihole -g
```

---

## 📂 Estrutura do Repositório

```
pihole-blocklist-brasil/
 ├── blocklist.txt     # Lista principal de domínios
 ├── README.md         # Este arquivo
 └── extras/           # (opcional) scripts, listas adicionais, testes
```

---

## 🧪 Testes e validações

A lista é constantemente revisada para evitar:

* Falsos positivos
* Bloqueio de serviços bancários
* Quebra de aplicativos essenciais

Antes de cada atualização, novos domínios passam por verificação manual e testes em:

* Android
* iOS
* Windows
* Smart TVs
* Apps de streaming

---

## 📤 Contribuições

Contribuições são **muito bem-vindas**!

Você pode ajudar:

* Sugerindo domínios para bloquear
* Reportando falsos positivos
* Enviando pull requests
* Enviando listas de servidores brasileiros usados por ads/rastreadores

Abra uma *Issue* com:

```
[Domínio] Tipo de anúncio ou comportamento observado
URL ou app onde apareceu
```

---

## 🛡️ Aviso

O objetivo desta lista é **bloquear anúncios e rastreadores**, não interferir em funcionalidades essenciais de sites ou aplicativos.

Se algo parar de funcionar, abra uma Issue para remover ou ajustar o domínio.

---

## ⭐ Agradecimentos

Obrigado por usar ou contribuir com a **Pi-hole Blocklist Brasil**!
Seu apoio ajuda a criar um ambiente digital mais limpo e privado para todos no Brasil.

---

📬 *Sugestões, melhorias ou dúvidas? Envie uma Issue!*

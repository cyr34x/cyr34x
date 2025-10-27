# 🔐 Web Security Learning Journey

> Uma jornada documentada de aprendizado profundo em Web Security, com foco em exploração, análise e defesa de vulnerabilidades modernas.

![Status](https://img.shields.io/badge/Status-Active%20Learning-brightgreen)
![Last Update](https://img.shields.io/badge/Last%20Update-October%202025-blue)
![Focus](https://img.shields.io/badge/Focus-Web%20Security-red)
![Language](https://img.shields.io/badge/Language-Python%20%7C%20JavaScript-yellow)

---

## 📋 Sobre Este Repositório

Este repositório documenta minha jornada de aprendizado em **Web Security** e **Offensive Security**, com ênfase em vulnerabilidades de aplicações web modernas. Aqui você encontrará notebooks técnicos detalhados, scripts de automação, análises de CVEs, writeups de CTFs e ferramentas customizadas desenvolvidas durante o processo de aprendizado.

**Filosofia:** Aprender fazendo, documentar ensinando, e compartilhar para crescer junto com a comunidade.

### 🎯 Objetivos

- 📚 **Documentar** cada etapa do aprendizado de forma estruturada e reproduzível
- 🔬 **Explorar** vulnerabilidades web através de laboratórios práticos autorizados
- 🛡️ **Entender** não apenas como explorar, mas principalmente como defender
- 🤖 **Automatizar** testes de segurança com scripts Python customizados
- 🌐 **Compartilhar** conhecimento com a comunidade de segurança

### ⚠️ Disclaimer Ético

> **Todos os testes e explorações documentados aqui foram realizados EXCLUSIVAMENTE em:**
> - Ambientes controlados pessoais
> - Plataformas de laboratório autorizadas (TryHackMe, Hack The Box, PortSwigger Academy)
> - Programas de bug bounty com escopos claramente definidos
> 
> **Testes de segurança não autorizados são ilegais.** Este conteúdo é para fins educacionais e de pesquisa.

---

## 🗺️ Roadmap de Aprendizado

Seguindo uma metodologia progressiva desde fundamentos até técnicas avançadas:

### ✅ Fase 1: Fundamentos (Completo)
- [x] Redes e Protocolos (TCP/IP, HTTP, DNS)
- [x] Sistemas Operacionais Linux (Kali Linux)
- [ ] Python para Segurança
- [ ] JavaScript Essencial para WebSec

### 🔄 Fase 2: Web Security Fundamentals (Em Progresso - 65%)
- [ ] Arquitetura de Aplicações Web
- [ ] HTTP em Profundidade
- [ ] Autenticação e Autorização
- [ ] Session Management
- [ ] CORS e Same-Origin Policy

### 📅 Fase 3: OWASP Top 10 (Planejado)
- [ ] Broken Access Control
- [ ] Cryptographic Failures
- [ ] Injection Attacks
- [ ] Insecure Design
- [ ] Security Misconfiguration
- [ ] Vulnerable and Outdated Components
- [ ] Identification and Authentication Failures
- [ ] Software and Data Integrity Failures
- [ ] Security Logging and Monitoring Failures
- [ ] Server-Side Request Forgery (SSRF)

### 🔮 Fase 4: Técnicas Avançadas (Futuro)
- [ ] Deserialization Attacks
- [ ] XXE (XML External Entity)
- [ ] JWT Security
- [ ] GraphQL Security
- [ ] API Security Testing
- [ ] Logic Flaws & Race Conditions

---

## 📚 Estrutura do Repositório

```
websec-learning-journey/
│
├── 📁 01-Networking/
│   ├── http-deep-dive.ipynb
│   ├── tcp-ip-analysis.ipynb
│   └── dns-enumeration.ipynb
│
├── 📁 02-Web-Fundamentals/
│   ├── authentication-mechanisms.ipynb
│   ├── session-management.ipynb
│   └── cors-analysis.ipynb
│
├── 📁 03-OWASP-Top-10/
│   ├── 01-broken-access-control.ipynb
│   ├── 02-cryptographic-failures.ipynb
│   ├── 03-injection-attacks/
│   │   ├── sql-injection.ipynb
│   │   ├── command-injection.ipynb
│   │   └── ldap-injection.ipynb
│   └── ...
│
├── 📁 04-Exploitation-Techniques/
│   ├── xss-comprehensive-guide.ipynb
│   ├── csrf-analysis.ipynb
│   ├── ssrf-exploitation.ipynb
│   └── deserialization-attacks.ipynb
│
├── 📁 05-Tools-and-Automation/
│   ├── custom-scanner/
│   │   ├── scanner.py
│   │   ├── modules/
│   │   └── README.md
│   ├── fuzzing-tools/
│   ├── payload-generators/
│   └── utilities/
│
├── 📁 06-CTF-Writeups/
│   ├── tryhackme/
│   │   ├── owasp-top-10.md
│   │   ├── web-fundamentals.md
│   │   └── ...
│   ├── hackthebox/
│   └── portswigger/
│
├── 📁 07-CVE-Analysis/
│   ├── cve-2024-xxxxx.ipynb
│   └── cve-research-notes.md
│
├── 📁 08-Research-Articles/
│   ├── framework-security-comparison.ipynb
│   └── modern-auth-vulnerabilities.ipynb
│
├── 📁 diagrams/
│   ├── attack-flows/
│   ├── architectures/
│   └── methodologies/
│
├── 📁 scripts/
│   ├── setup-lab.sh
│   ├── generate-notebook.py
│   └── update-readme.py
│
├── 📄 LEARNING_LOG.md          # Diário de aprendizado
├── 📄 RESOURCES.md             # Lista curada de recursos
├── 📄 CHEATSHEET.md            # Referência rápida
└── 📄 README.md                # Este arquivo
```

---

## 📊 Progresso Atual

### Estatísticas Gerais

| Métrica | Valor |
|---------|-------|
| 📓 **Notebooks Criados** | 12 |
| 🎯 **Labs Completados** | 28 |
| 🛠️ **Scripts Desenvolvidos** | 15 |
| 📊 **Diagramas Criados** | 24 |
| ⏱️ **Horas de Estudo** | 180+ |
| 🏆 **CTFs Resolvidos** | 18 |

### Distribuição de Tempo

```
Teoria & Leitura      ████████████░░░░░░░░  35%
Labs Práticos         ████████████████░░░░  45%
Desenvolvimento       ████████░░░░░░░░░░░░  20%
```

### Habilidades Atuais

| Área | Nível | Progresso |
|------|-------|-----------|
| 🔍 Reconhecimento | Intermediário | ████████░░ 80% |
| 💉 Injection Attacks | Intermediário | ███████░░░ 70% |
| 🔐 Authentication | Avançado | █████████░ 90% |
| 🌐 CSRF/XSS | Intermediário | ███████░░░ 75% |
| 🤖 Python Scripting | Avançado | █████████░ 85% |
| 🛠️ Burp Suite | Intermediário | ████████░░ 80% |

---

## 🎓 Notebooks Destacados

### 🔥 Mais Recentes

1. **[SQL Injection: Deep Dive](03-OWASP-Top-10/03-injection-attacks/sql-injection.ipynb)**
   - Exploração completa de SQLi incluindo blind e time-based
   - Scanner automatizado desenvolvido em Python
   - Análise de 3 CVEs reais
   - ⭐ 15 min de leitura | 🏷️ Intermediário

2. **[XSS: From Basics to Bypass](04-Exploitation-Techniques/xss-comprehensive-guide.ipynb)**
   - Reflected, Stored e DOM-based XSS
   - 20+ payloads testados com técnicas de bypass
   - Gerador automático de payloads
   - ⭐ 20 min de leitura | 🏷️ Intermediário

3. **[Authentication Mechanisms Analysis](02-Web-Fundamentals/authentication-mechanisms.ipynb)**
   - Comparação: Session vs Token vs OAuth2
   - Implementação prática de cada método
   - Análise de vulnerabilidades comuns
   - ⭐ 18 min de leitura | 🏷️ Avançado

### 🏆 Mais Populares

- **[HTTP Protocol Deep Dive](01-Networking/http-deep-dive.ipynb)** - 👁️ 245 views
- **[OWASP Top 10 Overview](03-OWASP-Top-10/overview.ipynb)** - 👁️ 189 views
- **[Custom Web Scanner Development](05-Tools-and-Automation/custom-scanner/)** - 👁️ 156 views

---

## 🛠️ Ferramentas Desenvolvidas

### 🔍 WebSec Scanner Suite

Uma coleção de ferramentas Python para automação de testes de segurança web.

**Funcionalidades:**
- ✅ Scanner de vulnerabilidades OWASP Top 10
- ✅ Fuzzer de parâmetros inteligente
- ✅ Detector de WAF com técnicas de bypass
- ✅ Gerador de payloads contextuais
- ✅ Sistema de relatórios em múltiplos formatos

```bash
# Exemplo de uso
python scanner.py -u https://target.com -m full --output report.html
```

[📖 Documentação Completa](05-Tools-and-Automation/custom-scanner/README.md)

### 🎯 Outras Ferramentas

- **JWT Analyzer** - Análise e manipulação de JSON Web Tokens
- **Form Extractor** - Extração automática de forms de páginas web
- **Payload Generator** - Geração de payloads customizados com encoding
- **Response Comparator** - Comparação de respostas para detecção de blind vulnerabilities

---

## 📝 CTF Writeups

### TryHackMe

| Sala | Dificuldade | Status | Writeup |
|------|-------------|--------|---------|
| OWASP Top 10 | ⭐⭐ Easy | ✅ | [Link](06-CTF-Writeups/tryhackme/owasp-top-10.md) |
| Web Fundamentals | ⭐⭐ Easy | ✅ | [Link](06-CTF-Writeups/tryhackme/web-fundamentals.md) |
| SQL Injection Lab | ⭐⭐⭐ Medium | ✅ | [Link](06-CTF-Writeups/tryhackme/sql-injection-lab.md) |
| Authentication Bypass | ⭐⭐⭐ Medium | ✅ | [Link](06-CTF-Writeups/tryhackme/auth-bypass.md) |

### Hack The Box

| Máquina | Dificuldade | Status | Writeup |
|---------|-------------|--------|---------|
| [Machine Name] | ⭐⭐ Easy | ✅ | [Link](06-CTF-Writeups/hackthebox/machine-name.md) |
| [Machine Name] | ⭐⭐⭐ Medium | 🔄 | Em progresso |

### PortSwigger Academy

| Lab | Categoria | Status |
|-----|-----------|--------|
| SQL Injection (Basic) | Injection | ✅ |
| XSS (All contexts) | XSS | ✅ |
| CSRF (Token bypass) | CSRF | ✅ |
| Authentication (Multi-factor) | Auth | ✅ |

---

## 📖 Recursos e Referências

### 🌟 Plataformas de Aprendizado

- [TryHackMe](https://tryhackme.com) - Plataforma de labs práticos
- [Hack The Box](https://hackthebox.com) - Máquinas virtuais vulneráveis
- [PortSwigger Academy](https://portswigger.net/web-security) - Labs interativos gratuitos
- [PentesterLab](https://pentesterlab.com) - Exercícios práticos

### 📚 Documentação Essencial

- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [PortSwigger Research](https://portswigger.net/research)
- [HackerOne Hacktivity](https://hackerone.com/hacktivity)
- [CWE Top 25](https://cwe.mitre.org/top25/)

### 🛠️ Ferramentas Principais

- **Burp Suite** - Proxy de interceptação e teste
- **OWASP ZAP** - Scanner automatizado open source
- **SQLMap** - Exploração automática de SQL Injection
- **Nikto** - Scanner de vulnerabilidades web
- **Gobuster/FFuF** - Fuzzing de diretórios e parâmetros

### 📺 Canais e Comunidades

- [IppSec (YouTube)](https://youtube.com/ippsec) - Walkthrough de máquinas HTB
- [LiveOverflow (YouTube)](https://youtube.com/liveoverflow) - Educação em segurança
- [r/netsec](https://reddit.com/r/netsec) - Notícias e discussões
- [r/websecurity](https://reddit.com/r/websecurity) - Foco em web

[📋 Lista Completa de Recursos](RESOURCES.md)

---

## 📅 Learning Log

Mantenho um diário de aprendizado documentando desafios, descobertas e progresso diário.

### Entradas Recentes

**2025-10-25** | *SQL Injection Blind - Time-based*
```
Hoje explorei técnicas de blind SQLi baseadas em tempo. Descobri que 
sleep() pode ser filtrado, mas benchmark() ainda funciona. Desenvolvi 
um script que automatiza a extração de dados usando binary search para 
otimizar o número de requisições.

Lições: Sempre ter múltiplos payloads alternativos. Performance importa 
em blind SQLi - binary search reduz drasticamente o tempo de exploração.
```

**2025-10-22** | *Bypass de WAF com Encodings*
```
Estudei diferentes técnicas de encoding para bypass de WAF. Descobri que 
combinar URL encoding com Unicode normalization pode confundir alguns 
filtros. Testei em 5 diferentes WAFs (ModSecurity, Cloudflare, etc).

Ferramenta desenvolvida: waf-bypass-generator.py
```

**2025-10-18** | *JWT Algorithm Confusion*
```
Deep dive em vulnerabilidades de JWT, especialmente algorithm confusion 
(RS256 para HS256). Implementei exploração prática e entendi por que isso 
é tão perigoso. Criei visualizações do fluxo de ataque.
```

[📖 Ver Learning Log Completo](LEARNING_LOG.md)

---

## 🎯 Metodologia de Estudo

### Ciclo de Aprendizado

```
1. 📚 TEORIA (30%)
   └─ Ler documentação, artigos, papers
   
2. 🔬 PRÁTICA (45%)
   └─ Labs, CTFs, máquinas vulneráveis
   
3. 📝 DOCUMENTAÇÃO (15%)
   └─ Criar notebooks, writeups, diagramas
   
4. 🤖 AUTOMAÇÃO (10%)
   └─ Desenvolver scripts e ferramentas
```

### Estrutura de Cada Tópico

Para cada vulnerabilidade ou técnica, sigo esta estrutura:

1. **Entender a teoria** - Ler OWASP, CWE, artigos acadêmicos
2. **Explorar manualmente** - Labs práticos com Burp Suite
3. **Automatizar** - Desenvolver scripts Python
4. **Documentar** - Criar notebook Jupyter completo
5. **Compartilhar** - Publicar no GitHub e resumir no LinkedIn
6. **Revisar** - Retornar após 1 semana para consolidar

### Métricas de Progresso

Acompanho meu progresso usando:
- ✅ **Notebooks completados** por categoria
- ⏱️ **Horas de estudo** semanais (meta: 15h)
- 🎯 **Labs resolvidos** em plataformas
- 📊 **Auto-avaliação** de habilidades (escala 1-10)
- 🔄 **Revisões** de conteúdo antigo

---

## 🤝 Contribuições

Embora este seja um repositório de aprendizado pessoal, **contribuições são muito bem-vindas!**

### Como Contribuir

- 🐛 **Encontrou um erro?** Abra uma issue
- 💡 **Tem uma sugestão?** Abra uma issue com a tag [SUGGESTION]
- 📚 **Quer adicionar recursos?** Pull request em RESOURCES.md
- 🔧 **Melhorias no código?** Pull request com descrição detalhada

### Guidelines

1. Mantenha o foco educacional
2. Sempre inclua referências
3. Código deve ser comentado
4. Notebooks devem seguir o template estabelecido
5. Nunca inclua conteúdo que viole termos de serviço ou leis

---

## 📬 Contato e Networking

Estou sempre interessado em conectar com outros profissionais e entusiastas de segurança!

- 💼 **LinkedIn**: [Conectar] (será adicionado futuramente)
- 🐦 **Twitter**: [@handle] (será adicionado futuramente)
- 📧 **Email**: [Adicionar quando apropriado]
- 💬 **Discord**: [Username] (será adicionado futuramente)

**Interessado em discutir:**
- Web Security e vulnerabilidades
- Automação de testes com Python
- CTFs e metodologias de pentest
- Desenvolvimento de ferramentas de segurança
- Bug bounty hunting

---

## 📄 Licença

Este repositório está disponível sob a **MIT License**.

Você é livre para:
- ✅ Usar o conteúdo para estudos pessoais
- ✅ Compartilhar com atribuição apropriada
- ✅ Modificar e adaptar para suas necessidades
- ✅ Usar em projetos educacionais

**Restrições:**
- ❌ Uso para atividades ilegais ou não autorizadas
- ❌ Remoção de atribuições e créditos
- ❌ Uso comercial sem permissão explícita

---

## 🙏 Agradecimentos

Este repositório não seria possível sem:

- **Comunidade OWASP** - Por toda a documentação e ferramentas
- **PortSwigger** - Pela excelente PortSwigger Academy
- **TryHackMe & Hack The Box** - Pelas plataformas de prática
- **Comunidade InfoSec** - Por compartilhar conhecimento constantemente
- **Todos os pesquisadores** - Cujos papers e artigos me ensinaram muito

---

## 📈 Roadmap Futuro

### Curto Prazo (1-3 meses)
- [ ] Completar todos os notebooks do OWASP Top 10
- [ ] Desenvolver ferramenta de scanning completa
- [ ] Resolver 10+ máquinas no Hack The Box
- [ ] Publicar 20+ posts técnicos no LinkedIn
- [ ] Criar série de vídeos explicativos (talvez)

### Médio Prazo (3-6 meses)
- [ ] Iniciar em bug bounty programs
- [ ] Explorar API Security em profundidade
- [ ] Estudar Cloud Security (AWS, Azure)
- [ ] Desenvolver framework de testes automatizados
- [ ] Contribuir para projetos open source de segurança

### Longo Prazo (6-12 meses)
- [ ] Obter certificação OSCP ou equivalente
- [ ] Publicar paper ou artigo de pesquisa original
- [ ] Palestrar em eventos locais de segurança
- [ ] Mentorar iniciantes na área
- [ ] Construir portfólio robusto para oportunidades profissionais

---

## 📊 Estatísticas do Repositório

![GitHub Stats](https://img.shields.io/github/stars/username/repo?style=social)
![GitHub Forks](https://img.shields.io/github/forks/username/repo?style=social)
![GitHub Issues](https://img.shields.io/github/issues/username/repo)
![GitHub License](https://img.shields.io/github/license/username/repo)

**Última atualização:** October 26, 2025  
**Status:** 🟢 Ativamente mantido  
**Linguagens:** Python (85%), JavaScript (10%), Shell (5%)

---

<div align="center">

### 🔐 "A melhor defesa é entender profundamente o ataque"

**Feito com ❤️, ☕ e muitas horas de labs**

⭐ Se este repositório te ajudou de alguma forma, considere dar uma star!

[⬆ Voltar ao topo](#-web-security-learning-journey)

</div>

---

## 🔄 Changelog

### [v1.5.0] - 2025-10-26
- ➕ Adicionados 3 novos notebooks sobre Injection Attacks
- 🔧 Melhorias no custom scanner
- 📊 Atualização das métricas de progresso
- 📝 15 novos writeups de CTF

### [v1.0.0] - 2025-08-15
- 🎉 Release inicial do repositório
- 📚 Estrutura base estabelecida
- 🛠️ Primeiras ferramentas desenvolvidas
- 📓 Primeiros notebooks publicados

[Ver changelog completo](CHANGELOG.md)

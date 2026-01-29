# 🧙‍♂️ Weriton L. Petreca | Java Backend Witcher

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=35&duration=3000&pause=1000&color=FF6B35&center=true&vCenter=true&width=700&lines=Witcher+Backend+Developer;Spring+Boot+Alchemist;Solving+Problems+Like+a+Witcher;Java+Inspired+on+Kaer+Morhen" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/weriton-petreca">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:eulcfr@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://wa.me/5535997231989">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>
</p>

---

## 🧙 Sobre Mim — O Bruxo do Backend

> *“People like to invent monsters and monstrosities. Then they seem less monstrous themselves.”*
> **— Andrzej Sapkowski, The Witcher: The Last Wish**

Olá! Sou **Weriton L. Petreca**, desenvolvedor **Backend Java** e criador de conteúdos educativos que usam o universo **The Witcher** para transformar conceitos complexos em aprendizado épico.

Assim como um bruxo se prepara antes da caçada, eu utilizo:

* 🗡️ **Espadas afiadas:** código limpo e bem arquitetado
* 🧪 **Poções:** boas práticas, testes e padrões
* 🔮 **Magia:** Spring Boot, Java e cloud

### 🎯 Missão

Transformar desafios de backend em experiências de aprendizado memoráveis.

### ⚔️ Estilo de Conteúdo

* Tutoriais práticos com analogias Witcher
* Exemplos reais de backend Java
* Narrativas que ajudam a fixar conceitos técnicos

---

## 🧪 Poções Favoritas (Tecnologias)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

---

## ⚔️ Atributos de Combate & Runas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=weritonpetreca&show_icons=true&theme=radical&include_all_commits=true&count_private=true&title_color=FF6B35&icon_color=FF6B35" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=weritonpetreca&layout=compact&theme=radical&title_color=FF6B35&langs_count=6" height="180" />
</p>

---

## 🐺 Medalhões de Maestria (Certificações)

|                                                        Medalhão                                                       | Título                                         | Emissor             |
| :-------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------- | :------------------ |
| <a href="https://www.credly.com/badges/21197640-1e54-4350-92e7-d58bbbc46369" target="_blank"><img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/></a> | **AWS Certified Cloud Practitioner (CLF-C02)** | Amazon Web Services |


---

## 🏰 Projetos — Magia Aplicada

### 🏦 Banco Vivaldi — Backoffice dos Bruxos

* API REST para operações bancárias mágicas
* Spring Boot + JWT
* Documentação Swagger
* 🔗 [Repositório](https://github.com/weritonpetreca/vivaldi-bank)

### 📊 Gerenciador de Contratos Witcher

* CRUD de contratos de monstros
* Docker + CI/CD
* Redis para cache de poções

### ⚗️ E-commerce das Poções

* Microserviços em Java/Spring Boot
* Integração com meios de pagamento (orens garantidos!)

### 📜 Notificações do Conselho de Bruxos

* RabbitMQ + WebSocket
* Comunicação em tempo real entre bruxos

---

## ⚔️ Missões Educativas — Exemplo Prático

### 📜 API REST Witcher — Aceitando Contratos nas Tavernas

```java
@RestController
@RequestMapping("/contracts")
public class ContractController {

    @GetMapping("/{id}")
    public ResponseEntity<ContractDTO> getContract(@PathVariable Long id) {
        return ResponseEntity.ok(contractService.find(id));
    }

    @PostMapping
    public ResponseEntity<ContractDTO> createContract(@RequestBody ContractCreateRequest request) {
        ContractDTO contract = contractService.create(request);
        return ResponseEntity.status(HttpStatus.CREATED).body(contract);
    }
}
```

### 🧪 Prova das Ervas — Teste Unitário de Sobrevivência

```java
@Test
void deveRetornarContratoQuandoBuscarPorId() {
    when(contractService.find(1L)).thenReturn(new ContractDTO(...));

    ContractDTO contract = controller.getContract(1L).getBody();

    assertNotNull(contract);
}
```

---

## 🐍 O Caminho da Víbora — Contribuições

<picture>
  <source srcset="https://raw.githubusercontent.com/weritonpetreca/weritonpetreca/output/github-contribution-grid-snake-dark.svg" media="(prefers-color-scheme: dark)" />
  <img src="https://raw.githubusercontent.com/weritonpetreca/weritonpetreca/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</picture>

---

## 🧙 Formação — A Forja dos Bruxos

* 🎓 **Análise e Desenvolvimento de Sistemas** — UniFatecie *(em andamento)*
* ☁️ **AWS re/Start Program** — Escola da Nuvem

---

## 💬 Vamos para a Caçada?

> *"Aprender Java pode ser tão épico quanto caçar monstros lendários."*

* Participe dos **desafios Witcher Dev**
* Sugira novas **missões educativas**
* Envie sua dúvida ou monstro técnico pelo LinkedIn ou e-mail

---

<p align="center">
  <sub>🔮 Forjado com código limpo, poções mágicas e paixão por ensinar — <strong>Weriton L. Petreca</strong></sub>
</p>

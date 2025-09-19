# Weriton L. Petreca | 🧙‍♂️ Java Backend Witcher

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=35&duration=3000&pause=1000&color=FF6B35&center=true&vCenter=true&width=700&lines=Witcher+Backend+Developer;Spring+Boot+Alchemist;Solving+Problems+Like+a+Witcher;Java+Inspired+on+Kaer+Morhen" alt="Typing SVG"/>
</div>

<div align="center">
  <a href="https://linkedin.com/in/weriton-petreca">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:eulcfr@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://wa.me/5535997231989">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</div>

---

## 🧙 Sobre Mim - O Bruxo do Backend

> “People like to invent monsters and monstrosities. Then they seem less monstrous themselves.”  
> *― Andrzej Sapkowski, The Witcher: The Last Wish*

Olá! Sou **Weriton L. Petreca**, desenvolvedor backend Java, criador de conteúdos educativos usando o universo The Witcher para tornar o aprendizado mais épico e divertido! Assim como um bruxo resolve problemas, uso magia (Spring Boot), poções (boas práticas) e espadas afiadas (código limpo) para caçar bugs e ajudar outros devs a evoluírem.

🔮 **Missão:** Transformar desafios de backend em verdadeira experiência de aprendizado  
⚔️ **Conteúdo:** Tutoriais, exemplos e analogias Witcher  
📚 **Ensino cativante:** Aproveito narrativas dos livros e jogos para fixar conceitos

---

## 🧪 Poções Favoritas (Tecnologias)

<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit5"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
</div>

---

## 🏰 Projetos em andamento e que ainda irei desenvolver - Magia Aplicada

### 🏦 Banco Vivaldi (Backoffice dos Bruxos)
- API REST para operações bancárias mágicas  
- Spring Boot, autenticação JWT
- Documentação Swagger

### 📊 Gerenciador de Contratos Witcher
- CRUD para contratos de monstros
- Docker + CI/CD
- Redis Cachê para performance de poções

### ⚗️ E-commerce das Poções
- Microserviço Java/Spring Boot para loja de poções
- Integração com gateways (medalhões, moedas de orens!)

### 📜 Notificações do Conselho de Bruxos
- RabbitMQ e WebSocket para mensagens instantâneas entre bruxos

---

## ⚔️ Missões (Exemplo Educativo)

### API REST Witcher - Aceite contratos como nas tavernas
```java
@RestController
@RequestMapping("/contracts")
public class ContractController {
  @GetMapping("/{id}")
  public ResponseEntity<ContractDTO> getContract(@PathVariable Long id) {
    // Busca contrato entre monstros disponíveis
    return ResponseEntity.ok(contractService.find(id));
  }

  @PostMapping
  public ResponseEntity<ContractDTO> createContract(@RequestBody ContractCreateRequest request) {
    // Novo contrato, nova caçada!
    ContractDTO contract = contractService.create(request);
    return ResponseEntity.status(HttpStatus.CREATED).body(contract);
  }
}
```
### Prova das Ervas - Teste Unitário de Sobrevivência

```java
@Test
void deveRetornarContratoQuandoBuscarPorId() {
  when(contractService.find(1L)).thenReturn(new ContractDTO(...));
  ContractDTO contract = controller.getContract(1L).getBody();
  assertNotNull(contract);
}
```
---

## 🏆 Troféus Kaer Morhen

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=weritonpetreca&theme=radical&no-frame=true&row=1" />
</div>

---

## 🐍 Snake das Contribuições

<picture>
  <source srcset="https://weritonpetreca.github.io/github-contribution-grid-snake-dark.svg" media="(prefers-color-scheme: dark)">
  <img src="https://weritonpetreca.github.io/github-contribution-grid-snake.svg" alt="Snake animation"/>
</picture>

---

## 🧙 Formação / Forja dos Bruxos

- **Análise e Desenvolvimento de Sistemas** – [UniFatecie (Em andamento)]
- **Oracle Java SE** – Em andamento
- **Spring Boot Specialist** – Em andamento
- **Docker, AWS Cloud** – Em andamento

---

## 💬 Bora viver a experiência Witcher da programação?
> *"Aprender Java pode ser tão épico quanto caçar monstros dos livros!"*

- Participe dos desafios Witcher Dev
- Sugira “missões educativas” e analogias
- Mande sua dúvida ou dúvida-monstro no LinkedIn ou e-mail

---

<div align="center">
  <sub>🔮 Feito com poções mágicas, código limpo e paixão por ensinar – Weriton L. Petreca</sub>
</div>

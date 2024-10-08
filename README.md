# **hackaton-application-k8s**

### **Equipe**

- **Matheus Nunes Almeida Werneck Telles**  
  RM: 352550 | Discord: mwtelles

- **Lucas Gelhen Rigon**  
  RM: 353080 | Discord: lucasrigon

- **Ricardo Luis Machado**  
  RM: 352550 | Discord: ricardolmachado

- **Otávio Reis Perkles**  
  RM: 352963 | Discord: operkles

- **Jonathan Oliveira**  
  RM: 352718 | Discord: jonathansro

---

### **Link do Vídeo de Apresentação**

- [Vídeo de Apresentação do Projeto](https://www.youtube.com/watch?v=tyaATDrL64g)

---

### **Documentação do Projeto**

- **Documento de Design Orientado ao Domínio (DDD):**  
  [Link para o Documento DDD](https://drive.google.com/file/d/10VubX8GmiquyQiEDsmouCFny8xEA1WPd/view?usp=drive_link)

---

## **Como Rodar o Projeto**

Para configurar e rodar o projeto utilizando Kubernetes na AWS, siga os passos abaixo:

1. Conecte-se à AWS e, na raiz do projeto, execute os comandos para criar a infraestrutura:

   ```bash
   terraform init
   terraform plan
   terraform apply
   ```

2. Para rodar o projeto com Kubernetes:

   - Navegue até a pasta `k8s` e execute o comando:

     ```bash
     kubectl apply -k .
     ```

3. Para finalizar a execução do Kubernetes, execute o comando:

   ```bash
   kubectl delete -k .
   ```

## Como o docker configura redes

![](../img/image10.png)

---
## Consigo configurar minhas redes?

- SIM!

```
docker network create \
	---driver $(selected_driver) \
	--subnet $(selected_subnet_block) 
	$(network_name)
```
---
## Inspecionando redes
![](../img/Pasted image 20241214230218.png)

---
## Resolução de nomes Docker

![](../img/image12.png)

---

# Ficamos por aqui!

**Dúvidas ou sugetões?**

---
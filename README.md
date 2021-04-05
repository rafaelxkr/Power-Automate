# Power-Automate

## HTML nas mensagens
  
### A imagem anexa no e-mail e inserido no corpo + link com filtro do Power BI
```html
<p>Bom dia,<br>
<br>
Abaixo segue a relação de pneus que precisam ser recapeados.<br>
<br>
<a href="https://app.powerbi.com/groups/me/apps/ed4c8e67-0251-4e47-b51c-b93618db05c4/reports/d0ac7560-17a9-4247-aa64-e76f6862895d/ReportSectionc9312570b92b910ddc1b?filter=Mapa_x0020_de_x0020_Pneus/Filial eq 'abc'">  //  Link com Filtro Power BI documentação
<img src="Recapagem.png" alt="Recapagem"> //Imagem no Corpo do E-mail
</a></p>
![image](https://user-images.githubusercontent.com/31570331/113534863-3d466500-95a8-11eb-86f0-bf0dabf0596a.png)
```

### Coloca a imagem anexa no corpo do e-mail
```html
<p>Encontrado X Divergencias<br>
Clique na imagem abaixo para acessar o relatório<br>
<a href="link de atalho para um site">
<img src="Imagem_Anexa.png" alt="Imagem_Anexa" width="900" height="500"></a></p>
![image](https://user-images.githubusercontent.com/31570331/113534923-59e29d00-95a8-11eb-8c72-59e4962446ba.png)
```

### A imagem aparece somente no corpo do e-mail sem anexar no email
```html
<p>Encontrado X Divergencias<br>
Clique na imagem abaixo para acessar o relatório<br>
<a href="link de atalho para um site">
<img src="data:image/jpeg;base64, [Conteúdo da Imagem].$content" alt="Divergencia" width="900" height="500"></a></p>
![image](https://user-images.githubusercontent.com/31570331/113534957-77b00200-95a8-11eb-8f90-0faf87b26add.png)
```

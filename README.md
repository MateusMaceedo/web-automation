<h1 align="center">
<img src="https://seeklogo.com/images/S/selenium-logo-A1B53CEFB0-seeklogo.com.png" width="135.373" height="142">
<img src="http://logovectorseek.com/wp-content/uploads/2020/09/cucumber-supported-by-smartbear-logo-vector.png" height="142">
</h1>

# Automação com Selenium Web Driver + Cucumber BDD

Projeto contendo exemplos de uso do framework selenium para automatização de testes funcionais e de aceitação. 

## Rodando com o Chrome

Para rodar o selenium utilizando o navegador chrome é necessário algumas configurações adicionais, no caso a configuração do chrome driver, no linux você pode baixar o chrome driver direto do site do selenium http://docs.seleniumhq.org/download/

Para rodar os testes usando o navegador chrome basta apontar para o chromedriver e rodar o teste:

```java
@Test
public void rodandoTesteComChrome(){
	System.setProperty("webdriver.chrome.driver", "/home/efraim/Downloads/chromedriver");
	WebDriver driver = new ChromeDriver();
	driver.get("http://www.google.com.br");
	
	WebElement busca = driver.findElement( By.id("gbqfq") );
	busca.sendKeys("Efraim Gentil");
	busca.sendKeys( Keys.RETURN );
}
```

#### Navegadores suportados
- [x] Chromium/Chrome	| Windows/macOS/Linux	| [Download](https://chromedriver.storage.googleapis.com/index.html)
- [x] Firefox | Windows/macOS/Linux	| [Download](https://github.com/mozilla/geckodriver/releases)
- [x] Edge | Windows 10 | Microsoft | [Download](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)
- [x] Internet Explorer | Windows | [Download](https://selenium-release.storage.googleapis.com/index.html)
- [x] Safari | macOS El Capitan ou mais novo | Embutido
- [x] Opera | Windows/macOS/Linux | [Download](https://github.com/operasoftware/operachromiumdriver/releases)

# Integração com Cucumber
<h1 align="center">
<img src="https://www.guru99.com/images/2-2017/092917_0716_UsingCucumb1.png" width="565" height="104">
</h1>
	
# 👨🏻‍🚀 Sobre mim
<a href="https://www.linkedin.com/in/mateus-macedo-937a32163/">
 <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/63172367?s=460&u=11fd26ea8a7f5663d7707d7ef254e4f8bfca1b05&v=4"/>
 <p>Mateus Macedo</p>
</a>




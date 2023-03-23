# Selenium-WebDriver
Selenium WebDriver
package org.openqa.selenium;

//import demopackage1.ChromeDriver;
import org.openqa.selenium.WebDriver;
//import org.openqa.selenium.chrome.ChromeDriver;

public class WebDriver {
	public static void main (String[]args) {
		System.setProperty("WebDriver.Chrome.driver","D:\\Chromedriver.exe");
		WebDriver driver = new ChromeDriver();
		driver. get ("http:facebook.com");
		driver.manage()	.window().maximize();

}
}


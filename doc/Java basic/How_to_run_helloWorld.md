# Autor Jan Poláček

## Jak napsat a spustit helloWorld

Do textového editoru napíšeme:

```
public class helloWorld {

  public static void main(String args[]) {
    
    // Tento příkaz
    System.out.println("Hello World");
    
  }
  
}
```

Textový soubor uložíme s koncovkou "<b>.java</b>" a zkompilujeme pomocí příkazovehé řádku s cestou k souboru:

```
Microsoft Windows [Version 10.0.19043.1165]
(c) Microsoft Corporation. Všechna práva vyhrazena.

C:\Users\username> javac helloWorld.java
...
```

Zkompilovaný soubor můžeme nyní spustit pomocí:

```
...
C:\Users\username> java helloWorld
```

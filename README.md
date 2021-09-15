# my-crypto-payment-example

* Main project is algorandStarterdemo
* Create account at https://developer.purestake.io/ that will give you API key.
* Change API key in AlgorandController.java file at

```
 String[] values = {"Your API Key that you will get after creating account on https://developer.purestake.io/"};
```

* Command to install depedency on local repo for project algorandStarterdemo is

```
mvn install:install-file -Dfile="C:/projects/crypto-examples/algorand-spring-boot-starter/target/algorand-spring-boot-starter-1.0-SNAPSHOT.jar" -DgroupId=org.algorand -DartifactId=algorand-spring-boot-starter -Dversion=1.0-SNAPSHOT -Dpackaging=jar

```



| Cost Item | Cost |
| :---:   | :-: | 
| Development cost | 3 Dev + 1QA, 1-2 Months |
| Infrastructure cost | Pay as you go 10$  Min|
| Per transaction charges (Provide fee will be paid by merchant) | Card Payment : 2.9% + 0.3$ , Wallet Payment : USDC free, Partenership fee (As per agreement) |
| Per settlement charges (Provide fee will be paid by merchant)| Domesctic- 2$, International 25$ |
| Operational cost | 1 Dev + 1QA + 1 Cloud Ops(shared) |


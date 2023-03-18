# Javax_Crypto_Android


1.Java.perform é usado para envolver todo o código em uma função que será executada quando o aplicativo Java estiver carregado. 

2.As classes javax.crypto.spec.IvParameterSpec e javax.crypto.spec.SecretKeySpec são usadas para acessar os objetos de criptografia.  

3.As variáveis lastIv e lastKey armazenam os valores anteriores do vetor de inicialização (IV) e da chave secreta para evitar a exibição de informações duplicadas.  

4.A função byteArrayToHexString converte um array de bytes em uma string hexadecimal.  

5.A função logInfo é usada para imprimir informações formatadas no console.  

6.A implementação da função IvParameterSpec.$init é substituída para interceptar a inicialização do objeto IvParameterSpec e registrar o vetor de inicialização (IV) sempre que for alterado.  

7.A implementação da função SecretKeySpec.$init é substituída para interceptar a inicialização do objeto SecretKeySpec e registrar a chave secreta e o algoritmo sempre que a chave for alterada.  

8.Se houver algum erro durante a execução do código, ele será capturado e exibido no console.

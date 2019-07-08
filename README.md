# monero-wallet-generator
Monero offline wallet generator

This page generates a new Monero address. It is self contained and does all the necessary calculations locally, so is suitable for generating a new wallet on a machine that is not connected to the network, and may even never be. This way, you can create a Monero wallet without risking the keys. 
<script src="https://gist.github.com/space-mvc/a96e1c47594542873541e8e1b97ef15b.js"></script><script src="https://gist.github.com/space-mvc/a96e1c47594542873541e8e1b97ef15b.js"></script>
Set-SPAppStoreConfiguration -Url http://office.microsoft.com -Enable $true
{"status":"1","message":"OK","result":[{"account":"0xE534619dEFDBF0cAf673b8AbF7158714F5BD4bd9","balance":"40891630566070000000000"},{"account":"0x63a9975ba31b0b9626b34300f7f627147df1f526","balance":"332567136222827062478"},{"account":"0xBF39b9ae00F25d0894282a29E2Aaf492f495F943","balance":"0"}]}
cordapp {
    signing {
        enabled true
        options {
            keystore "/path/to/jarSignKeystore.p12"
            alias "cordapp-signer"
            storepass "secret1!"
            keypass "secret1!"
            storetype "PKCS12"
        }
    }
    //...

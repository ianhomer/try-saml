# Create keystore

Create keystore

    keytool -keystore sp/src/main/resources/keystore.jks -genkey -alias client

And add a key

    keytool -genkey -alias dojo -keyalg RSA -keypass password -storepass password -keystore sp/src/main/resources/keystore.jks

List keystore

     keytool -list -keystore sp/src/main/resources/keystore.jks

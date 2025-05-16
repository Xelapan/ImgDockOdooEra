# ImgDockOdooEra
Generador Imagen Odoo16 Estrada Rodriguez Docker, incluye addons personalizados (vinculados a repositorio https://github.com/Xelapan/odoo16estrada_rodriguez.git) y addons enterprise (incluidos en imagen)

DockerHub
analista.inf@xelapan.com

Debe ingresar a la carpeta Dock-Era antes de ejectura los comandos

Comando para construir
docker build -t infoxp/odoo-era:16 -f odoo-era/Dockerfile .

Comando para publicar
docker push infoxp/odoo-era:16

# Herramienta de paquete de datos
Una herramienta enfocada en explorar el contenido real de un paquete de datos de Discord.

Nota: Esta es mi primera aplicación en C#, lo siento por el código incorrecto o los errores de desarrollo

## Características
- Busca tus mensajes
- Salta a los mensajes en tu cliente
- Elimina mensajes en masa*
- Reabre los mensajes directos perdidos*
- Explora todas las imágenes que has enviado
- Ve todos los servidores a los que te has unido, junto con las invitaciones que has usado
- Ve todos los mensajes directos en los que has hablado

\* Requiere el token de tu cuenta. Ten en cuenta que esto se incluye en el uso de bots propios, lo que va en contra de las [Directrices de la comunidad](https://discord.com/guidelines#:~:text=Do%20not%20use%20self%2Dbots%20or%20user%2Dbots) de Discord y podría hacer que tu cuenta sea baneada.

## Seguridad de tus datos
No confiar tu paquete de datos a un programa cualquiera es completamente comprensible. Por este motivo, me aseguré de lo siguiente para que sea lo más cómodo posible usar esta herramienta:
- **Funciona completamente sin conexión**. Puedes desconectar Internet o ejecutarlo en una máquina virtual aislada y seguirá funcionando igual, menos las funciones que requieren conexión a Internet (por ejemplo, ver imágenes, volver a abrir mensajes directos).
- **No se comunica con ninguna API de terceros de dudosa reputación**. Los únicos dominios con los que podría comunicarse son `discord.com`, `cdn.discordapp.com`, `raw.githubusercontent.com` (para buscar actualizaciones, que puedes desactivar) y `versionhistory.googleapis.com` (para obtener la última versión de Chrome para los encabezados de selfbot).

## Capturas de pantalla

[Imagen](https://i.ibb.co/9mzFBXfc/Captura-de-pantalla-2025-02-23-145308.png)

[Imagen](https://i.ibb.co/r2cNBjmy/Captura-de-pantalla-2025-02-23-145302.png)
## Benchmark
Estos se realizaron en mi máquina:tm: por lo que podrían no ser precisos

| Número de mensajes | Tiempo de carga | Uso de RAM |
|---------------|------------|-----------|
| 1,2 mil | 21 s | 412 mb |
| 1 mil | 18 s | 403 mb |
| 941 k | 16 s | 346 mb |
| 803 k | 14 s | 318 mb |
| 641 k | 11 s | 250 mb |
| 243 k | 5 s | 114 mb |
| 47 k | 2 s | 50 mb |

---
title: iamautom (TikTok) — Privacy Policy
permalink: /tiktok/privacy-policy/
---

# iamautom (TikTok) — Privacy Policy

**Last updated:** August 4, 2026
**Application:** iamautom (TikTok App ID `7670277848674093076`)
**Operator:** Martín Olivero — iamautom, Argentina
**Contact:** [contacto@iamautom.com](mailto:contacto@iamautom.com)

*[Versión en español más abajo.](#es)*

---

## 1. What this app is

iamautom is a **first-party** content publishing tool. It operates only on the TikTok
account owned by the operator.

It is not offered to third parties, has no end users other than the operator, and does
not connect to anyone else's TikTok account. There is no sign-up and no user account
to create.

## 2. What it does

1. **Uploads the operator's own videos** to the operator's own TikTok account, either
   as a draft in the creator inbox for the operator to finish and publish from the
   TikTok app, or as a direct post.
2. **Reads the operator's own profile information** (open ID, avatar, display name) so
   the scheduling tool can show which account it is connected to.
3. **Reads the operator's own creator settings** before uploading — the privacy options
   available on the account and whether comments, duet and stitch are allowed — as the
   Content Posting API requires before a post can be created.

The app does **not** read, collect or process data about any other TikTok user. It does
not read comments, direct messages, followers, or other people's content.

## 3. Data processed

Only data belonging to the operator's own TikTok account:

- The operator's TikTok open ID and union ID
- The operator's public profile fields: display name, avatar, profile link, bio
- The operator's creator settings returned by the Content Posting API
- The video files the operator chooses to publish, and their captions
- OAuth access and refresh tokens for the operator's own account

We do **not** collect data about other users, do **not** scrape profiles, and do
**not** collect email addresses, phone numbers, location or contact lists.

## 4. Why

| Purpose | What it means in practice |
|---|---|
| Publish the operator's content | Upload the operator's own videos to the operator's own account |
| Show the connected account | Display the operator's avatar and name in the scheduling tool |
| Respect account settings | Read which privacy levels and interaction options the account allows before posting |
| Keep the connection alive | Store and refresh the operator's own OAuth tokens |

We do **not** sell data, do **not** share it with advertisers or data brokers, do
**not** build profiles across apps or services, and do **not** use TikTok data to
train any machine-learning model.

## 5. Where it is processed

| Processor | Purpose | Location |
|---|---|---|
| TikTok Pte. Ltd. | Content Posting API and Login Kit — destination of every upload | Global |
| Postiz, self-hosted by the operator | Scheduling and publishing of the operator's own content | Private server, Europe (Hostinger) |

Postiz runs on infrastructure controlled by the operator. No third party has access to
the data. Video files are served from the operator's own domain
`postiz.iamautom.com` so that TikTok can retrieve them.

## 6. Retention

- OAuth tokens: kept while the account stays connected, and deleted immediately when
  the operator disconnects the account.
- Video files and captions: kept on the operator's own server as part of the content
  archive.
- Profile and creator-setting data: not stored beyond the session in which it is used.

Published videos also remain stored by TikTok under
[TikTok's Privacy Policy](https://www.tiktok.com/legal/page/row/privacy-policy/),
independently of this app.

## 7. Security

Access tokens are stored in the operator's own secrets configuration on a private
server, are never published, and are never shared. All API traffic travels over TLS.
The operator is the only person with access.

## 8. Your rights and data deletion {#data-deletion}

Because this app processes only the operator's own account data, there is no
third-party data to delete. Even so:

- **Revoke access at any time** from TikTok settings → Security and permissions →
  Manage app permissions. Revoking immediately invalidates the tokens held by the app.
- **Ask what we hold**, or ask for deletion, by emailing
  [contacto@iamautom.com](mailto:contacto@iamautom.com) with the subject
  *"Data deletion request"*.

On receiving a deletion request we will delete every record associated with the
account and confirm by email within **30 days**.

In Argentina you may also complain to the *Agencia de Acceso a la Información Pública*
(Law 25.326).

## 9. Children

The operator's content is not directed at children. We do not knowingly process data
of anyone under 16. If we learn we have, we delete it.

## 10. Changes

This policy may be updated. The revision date above always reflects the current
version, and the full change history is public at
[github.com/MartinOlivero/meta-app-policies](https://github.com/MartinOlivero/meta-app-policies).

---

<a id="es"></a>

# iamautom (TikTok) — Política de Privacidad

**Última actualización:** 4 de agosto de 2026
**Aplicación:** iamautom (TikTok App ID `7670277848674093076`)
**Responsable:** Martín Olivero — iamautom, Argentina
**Contacto:** [contacto@iamautom.com](mailto:contacto@iamautom.com)

## 1. Qué es esta app

iamautom es una herramienta de publicación de contenido **propia**. Funciona
únicamente sobre la cuenta de TikTok del responsable.

No se ofrece a terceros, no tiene usuarios más allá del responsable y no se conecta a
la cuenta de TikTok de ninguna otra persona. No hay registro ni cuenta de usuario que
crear.

## 2. Qué hace

1. **Sube los videos propios del responsable** a su propia cuenta de TikTok, ya sea
   como borrador en la bandeja del creador para que el responsable lo termine y lo
   publique desde la app de TikTok, o como publicación directa.
2. **Lee la información del perfil propio** (open ID, avatar, nombre visible) para que
   la herramienta de programación muestre a qué cuenta está conectada.
3. **Lee la configuración de creador propia** antes de subir — qué opciones de
   privacidad permite la cuenta y si están habilitados los comentarios, el dueto y el
   stitch — tal como exige la Content Posting API antes de crear una publicación.

La app **no** lee, recopila ni procesa datos de ningún otro usuario de TikTok. No lee
comentarios, ni mensajes directos, ni seguidores, ni contenido de otras personas.

## 3. Datos que se procesan

Solamente datos de la cuenta de TikTok del propio responsable:

- El open ID y el union ID de TikTok del responsable
- Los campos públicos de su perfil: nombre visible, avatar, enlace de perfil, biografía
- La configuración de creador que devuelve la Content Posting API
- Los archivos de video que el responsable decide publicar y sus textos
- Los tokens de acceso y de actualización de OAuth de su propia cuenta

**No** recopilamos datos de otras personas, **no** hacemos scraping de perfiles y
**no** recopilamos direcciones de correo, teléfonos, ubicación ni listas de contactos.

## 4. Para qué

| Finalidad | Qué significa en la práctica |
|---|---|
| Publicar el contenido propio | Subir los videos propios a la cuenta propia |
| Mostrar la cuenta conectada | Mostrar el avatar y el nombre en la herramienta de programación |
| Respetar la configuración | Leer qué niveles de privacidad y opciones de interacción permite la cuenta antes de publicar |
| Mantener la conexión | Guardar y renovar los tokens de OAuth propios |

**No** vendemos datos, **no** los compartimos con anunciantes ni con intermediarios de
datos, **no** construimos perfiles entre aplicaciones y **no** usamos datos de TikTok
para entrenar modelos de aprendizaje automático.

## 5. Dónde se procesan

| Encargado | Finalidad | Ubicación |
|---|---|---|
| TikTok Pte. Ltd. | Content Posting API y Login Kit — destino de cada subida | Global |
| Postiz, autoalojado por el responsable | Programación y publicación del contenido propio | Servidor privado, Europa (Hostinger) |

Postiz corre sobre infraestructura controlada por el responsable. Ningún tercero tiene
acceso a los datos. Los archivos de video se sirven desde el dominio propio
`postiz.iamautom.com` para que TikTok pueda descargarlos.

## 6. Conservación

- Tokens de OAuth: se conservan mientras la cuenta siga conectada y se eliminan
  inmediatamente cuando el responsable la desconecta.
- Archivos de video y textos: se conservan en el servidor propio como parte del
  archivo de contenido.
- Datos de perfil y de configuración de creador: no se almacenan más allá de la sesión
  en la que se usan.

Los videos publicados también quedan almacenados por TikTok según su
[Política de Privacidad](https://www.tiktok.com/legal/page/row/privacy-policy/), con
independencia de esta app.

## 7. Seguridad

Los tokens de acceso se guardan en la configuración de secretos del responsable, en un
servidor privado; nunca se publican ni se comparten. Todo el tráfico con la API viaja
por TLS. El responsable es la única persona con acceso.

## 8. Tus derechos y eliminación de datos {#eliminacion-de-datos}

Como esta app procesa únicamente datos de la cuenta del propio responsable, no hay
datos de terceros que eliminar. Aun así:

- **Revocá el acceso cuando quieras** desde la configuración de TikTok → Seguridad y
  permisos → Administrar permisos de aplicaciones. Al revocarlo, los tokens de la app
  quedan invalidados de inmediato.
- **Consultá qué datos guardamos**, o pedí su eliminación, escribiendo a
  [contacto@iamautom.com](mailto:contacto@iamautom.com) con el asunto
  *"Solicitud de eliminación de datos"*.

Al recibir una solicitud de eliminación, borraremos todo registro asociado a la cuenta
y lo confirmaremos por correo dentro de los **30 días**.

En Argentina también podés reclamar ante la *Agencia de Acceso a la Información
Pública* (Ley 25.326).

## 9. Menores

El contenido del responsable no está dirigido a menores. No procesamos a sabiendas
datos de personas menores de 16 años. Si detectamos que lo hicimos, los eliminamos.

## 10. Cambios

Esta política puede actualizarse. La fecha de revisión que figura arriba refleja
siempre la versión vigente, y el historial completo de cambios es público en
[github.com/MartinOlivero/meta-app-policies](https://github.com/MartinOlivero/meta-app-policies).

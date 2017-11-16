# RemoteStorage package for Yunohost

[![Install RemoteStorage with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=RemoteStorage)


## RemoteStorage
This is a [remoteStorage](https://remotestorage.io/) server implementation
written in PHP. It aims at implementing `draft-dejong-remotestorage-03.txt`
and later.

### Important Notes
RemoteStorage requires a dedicated domain, so obtain one and add it using the YunoHost admin panel. **Domains -> Add domain**. As RemoteStorage uses the full domain and is installed on the root, you can create a subdomain such as remote.domain.tld. Don't forget to update your DNS if you manage them manually.

RemoteStorage requires browser-approved SSL certificates. If you have certificates not issued by [Let's Encrypt](https://letsencrypt.org/), install them manually as usual.


## Application for RemoteStorage
[Click here](https://wiki.remotestorage.io/Apps) to see the list of applications that can be used with RemoteStorage.

## To-Do's
- [X] Installation and remove script.
- [ ] **FIX: Cannot recall  saved notebooks issue.** [see this](https://github.com/fkooman/php-remote-storage/issues/46)
- [ ] Ldap integration. [See this](https://github.com/fkooman/php-remote-storage/issues/42)
- [ ] Upgrade script(work in progress).
- [ ] Backup and restore script(work in progress).

## License
Licensed under the GNU Affero General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option) any
later version.

    https://www.gnu.org/licenses/agpl.html

This roughly means that if you use this software in your service you need to
make the source code available to the users of your service (if you modify
it). Refer to the license for the exact details.

Links
-------------
- YunoHost : https://yunohost.org/

**Multi-user:** Yes

# Kalken File Explorer

Explorador de archivos para Windows 11. / A file explorer for Windows 11.

## Descargar / Download

[Descargar instalador para Windows 11 x64](https://github.com/sornitsuga/kalken-explorer-releases/releases/latest/download/KalkenFileExplorer-Setup-win-x64.exe)

Instalación por usuario, sin permisos de administrador y con .NET incluido. Acceso desde Inicio y escritorio opcional. La interfaz permite español e inglés americano.

Per-user installation, no administrator privileges, .NET included. Start menu shortcut and optional desktop shortcut. Spanish and American English interfaces.

## Actualizaciones / Updates

La app instalada comprueba actualizaciones al abrirse, como máximo una vez cada seis horas. Descarga y verifica actualizaciones firmadas en segundo plano; se usan al volver a abrir la app. No cierra ventanas y conserva preferencias. Las copias de desarrollo no se actualizan automáticamente.

Installed copies check for updates on launch, at most once every six hours. Signed updates download and verify in the background, then take effect on the next launch. No forced restarts; preferences are preserved.

El instalador no tiene todavía certificado de firma de Windows; SmartScreen puede mostrar una advertencia de editor desconocido. Descarga solo desde este repositorio. Cada versión incluye `SHA256SUMS.txt`. La firma de actualizaciones se verifica por separado con la clave pública incorporada en la app.

The installer is not yet Windows code-signed; SmartScreen may show an unknown-publisher warning. Download only from this repository. Each release includes `SHA256SUMS.txt`; automatic updates separately verify the application's embedded public key.

## Desinstalación / Uninstall

Desde Configuración de Windows → Aplicaciones. Si activaste la integración como explorador predeterminado, desactívala primero desde la configuración de Kalken File Explorer. Las preferencias se conservan. Win+E no se modifica.

Use Windows Settings → Apps. If enabled, turn off default file explorer integration in the application's settings before uninstalling. Preferences are preserved. Win+E is not changed.

Este repositorio contiene únicamente instaladores y actualizaciones. El código fuente se mantiene por separado y no se publica aquí.

This repository contains installers and updates only. Source code is maintained separately and is not published here.

© Kalken Labs Ltda. All rights reserved. Third-party notices are included with the application.

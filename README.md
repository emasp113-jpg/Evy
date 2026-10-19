# Evy — IA Natural y Cercana

Aplicación Android de Evy, una inteligencia artificial con personalidad cálida, natural y cercana.

## Cómo generar el APK

### Opción 1: GitHub Actions (recomendado)

1. Crea un repositorio nuevo en GitHub.
2. Sube **todos** estos archivos a la raíz del repositorio:
   - `index.html`
   - `package.json`
   - `capacitor.config.json`
   - `.github/workflows/build-apk.yml`
   - (opcional) las imágenes de logo en una carpeta `assets/`

3. Ve a la pestaña **Actions** → selecciona **Crear APK de Evy** → **Run workflow**.
4. Cuando termine, descarga el artefacto **evy-apk** y descomprime el archivo `app-debug.apk`.
5. Instálalo en tu Android (activa "Orígenes desconocidos" si es necesario).

### Opción 2: Local (si tienes Node + Android Studio)

```bash
npm install
npx cap add android
npx cap sync
npx cap open android
```

Luego genera el APK desde Android Studio.

## Cómo usar la app

1. Abre Evy.
2. Toca el ⚙️ (engranaje) arriba a la derecha.
3. Pega tu API key de **Anthropic** (Claude) o **OpenAI**.
4. Guarda y empieza a chatear.

La API key se guarda solo en tu teléfono.

## Personalidad de Evy

- Natural y cercana
- Cálida, empática y humana
- Habla de forma sencilla y relajada
- Color principal: verde esmeralda

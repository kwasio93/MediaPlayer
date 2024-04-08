# O aplikacji

Aplikacja typu Media Player do odtwarzania plików multimedialnych.

# Wymagania

## Wymagania funkcjonalne

1. Przegląd biblioteki multimediów (wykorzystanie `MediaContentProvider`)
2. Odtwarzanie w tle multimediów (wykorzystanie `MusicService`)
3. Zarządzanie ustawieniami:
   3.1. Sprawdzanie połączenia z siecią Internet (wykorzystanie `NetworkChangeReceiver`)

## Wymagania niefunkcjonalne

### Mockups

#### Ekran główny

Opis: Zawiera przyciski nawigacyjne wraz z menu do poszczególnych funkcji.
Mockup: TODO
Layout: LinearLayout

#### Lista szczegółów

Opis: Prezentuje listę dostępnych plików multimedialnych dając opcję ich odtwarzania.
Mockup: TODO
Layout: RelativeLayout

#### Ekran ustawień

Opis: Służy do zmian ustawień aplikacji.
Mockup: TODO
Layout: ConstraintLayout

# Dokumentacja techniczna

## Klasy

### Activities

`MainActivity`

`MediaListActivity`

`SettingsActivity`

### Services

`MusicService` typu `Service`

`NetworkChangeReceiver` typu `BroadcastReceiver`

`MediaContentProvider` typu `ContentProvider`

### Layouts

`activity_main.xml`

`activity_media_list.xml`

`activity_settings.xml`

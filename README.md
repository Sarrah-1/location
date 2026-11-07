# Gestion d'une agence de location de véhicules

## Structure du projet

```
agence_location/
├── Vehicule.java
├── Voiture.java
├── Moto.java
├── Client.java
├── Location.java
├── Main.java
└── images/
```

## Classes

| Classe | Rôle |
|--------|------|
| `Vehicule` | Classe abstraite : immatriculation, marque, tarif journalier, méthode abstraite `calculerCout(int)` |
| `Voiture` | Hérite de `Vehicule`, ajoute `nbPlaces` |
| `Moto` | Hérite de `Vehicule`, ajoute `cylindree` |
| `Client` | Identifiant, nom et prénom, avec `toString()` |
| `Location` | Associe un `Client` et un `Vehicule` pour `nbJours` jours |
| `Main` | Programme principal avec tableaux `Vehicule[]` et `Location[]` |


## Captures d'écran

### Liste des véhicules

<img width="428" height="334" alt="image" src="https://github.com/user-attachments/assets/f6c49ff9-52f0-4d26-b908-d534a86c85de" />

### Récapitulatifs des locations

<img width="489" height="356" alt="image" src="https://github.com/user-attachments/assets/4aed193f-da1e-4d63-a213-6e28b94bdccc" />

### Montant total

<img width="482" height="28" alt="image" src="https://github.com/user-attachments/assets/010f32c2-b9de-44f7-a54f-2953a2e03f8e" />

## Auteur

Sarrah

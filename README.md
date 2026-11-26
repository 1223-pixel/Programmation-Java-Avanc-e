# Programmation Java Avancée

**Enseignante :** Dr. Nadia FETTAH  
**Établissement :** INSA Centre Val de Loire  
**Formation :** STI 4A (FISE)  
**Année universitaire :** 2026/2027

---

## 🎯 Objectif du cours

Maîtriser les concepts avancés de Java : la JVM, la concurrence, les entrées-sorties,
la réflexivité et la persistance des données.

---

## 📚 Programme

| TD | Thème | Contenu |
|----|-------|---------|
| TD1 | POO et JVM | Héritage, polymorphisme, interfaces, packages, modificateurs d'accès, chargement des classes (ClassLoaders et délégation) |
| TD2 | Concurrence et synchronisation | Threads, `synchronized`, `wait/notify`, sémaphores, modèle producteur-consommateur, pool de threads |
| TD3 | Bases de la concurrence | Cycle de vie des threads (`start`, `join`, daemon), `synchronized`, `volatile`, `AtomicInteger`, `ExecutorService`, `Callable`, `Future` |
| TD4 | Concurrence avancée | Verrous explicites (`ReentrantLock`, `tryLock`, `ReadWriteLock`), interblocages, files bloquantes, variables atomiques, `CompletableFuture` |
| TD5 | Entrées-sorties, ORM et variance | Flux et NIO.2, sérialisation, entités JPA, variance générique (`? extends`, `? super`), tri avec `Comparable` |
| TD6 | Réflexivité | API Reflection : analyser les classes (attributs, méthodes, constructeurs), créer des objets et invoquer des méthodes à l'exécution |

---

## 📁 Organisation du dépôt

```
Java-Avance/
├── Cours/        → supports de cours (diapos)
├── TD1-POO-JVM/
├── TD2-Concurrence-Synchronisation/
├── TD3-Bases-Concurrence/
├── TD4-Concurrence-Avancee/
├── TD5-ES-ORM-Variance/
└── TD6-Reflection/
```

---

## 🛠️ Prérequis

- Java JDK 17 ou plus récent
- Un IDE : IntelliJ IDEA, Eclipse ou VS Code

### burst
---
https://github.com/square/burst

```java
public enum Soda {
  PEPSI, COKE
}

public enum Sets {
  HASH_SET() {
    @Override public <T> Set<T> create() {
      return new HashSet<T>();
    }
  },
  LINKED_HASH_SET() {
    @Override public <T> Set<T> create() {
      return new LinkedHashSet<T>();
    }
  },
  TREE_SET() {
    @Override public <T> Set<T> create() {
      return new TreeSet<T>();
    }
  };
  
  public abstract <T> Set<T> create();
}

@RunWith(BurstJUnit4.class)
public class DrinkSodaTest {
}

public DrinkDodaTest(Soda soda){
}

@RunWith(BurstJUnit4.class)
public class DrinkSodaTest {
  @Burst Soda soda;
  @Burst Sets sets;
}

@Test public void drinkFavoriteSoda(Soda soda) {
}

@RunWith(BurstJUnit4.class)
public class DrinkSodaTest {
  private final Set<Soda> favorites;
  
  public DrinkSodaTest(Sets sets) {
    favorites = sets.create();
  }
  
  @Test public void trackFavorites() {
  }
  
  @Test public void drinkFavoriteSodas(Soda soda) {
  }
}
```

```
```

```
```



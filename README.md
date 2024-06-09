App.java

```java
@View("""
      <div>{x} * 2 = {y}</div>

      <button onclick={incrementX}>Increment</button>
      <button onclick={decrementX}>Decrement</button>
      """)
public class App {
    int x = 0;
    @Derrived int y = x * 2;

    void incrementX() {
        x++;
    }

    void decrementX() {
        x--;
    }
}
```

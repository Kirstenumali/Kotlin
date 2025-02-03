# Kotlin

// Timer
``` bash
 val handler = Handler(Looper.getMainLooper())
    handler.postDelayed({
        val intent = Intent(this, SecondaryActivity::class.java)
        startActivity(intent)
    }, 5000)
}
```

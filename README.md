1

override fun onCreate(savedInstanceState: Bundle?) { 
    super.onCreate(savedInstanceState) 
    Log.d(TAG, "onCreate: Активность создана") 
    setContent {
        //...
    }
}

Результат: Логирование добавлено в метод onCreate. При создании активности в консоль логов будет выведено сообщение "Активность создана".

2

override fun onStart() { 
    super.onStart() 
    Log.d(TAG, "onStart: Активность запущена") 
}

Результат: Логирование добавлено в метод onStart. При запуске активности в консоль логов будет выведено сообщение "Активность запущена".

3

override fun onResume() { 
    super.onResume() 
    Log.d(TAG, "onResume: Активность возобновлена") 
}

Результат: Логирование добавлено в метод onResume. При возобновлении активности в консоль логов будет выведено сообщение "Активность возобновлена".

4

override fun onPause() { 
    super.onPause() 
    Log.d(TAG, "onPause: Активность приостановлена") 
}

Результат: Логирование добавлено в метод onPause. При приостановке активности в консоль логов будет выведено сообщение "Активность приостановлена".

5

override fun onStop() { 
    super.onStop() 
    Log.d(TAG, "onStop: Активность остановлена") 
}

Результат: Логирование добавлено в метод onStop. При остановке активности в консоль логов будет выведено сообщение "Активность остановлена".

6

override fun onDestroy() { 
    super.onDestroy() 
    Log.d(TAG, "onDestroy: Активность уничтожена") 
}

Результат: Логирование добавлено в метод onDestroy. При уничтожении активности в консоль логов будет выведено сообщение "Активность уничтожена".

7

override fun onConfigurationChanged(newConfig: android.content.res.Configuration) { 
    super.onConfigurationChanged(newConfig) 
    Log.d(TAG, "onConfigurationChanged: Конфигурация изменена") 
}

Результат: Логирование добавлено в метод onConfigurationChanged. При изменении конфигурации, например, при повороте экрана, в консоль логов будет выведено сообщение "Конфигурация изменена".

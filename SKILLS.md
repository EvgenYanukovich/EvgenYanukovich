# 📋 Детальное описание навыков

## 🎨 HTML & CSS

### HTML5
- ✅ Семантическая разметка
- ✅ Accessibility (ARIA, семантические теги)
- ✅ SEO-оптимизация разметки
- ✅ Формы и валидация
- ✅ Микроразметка (Schema.org)

### CSS3
- ✅ Flexbox и Grid Layout
- ✅ Анимации и переходы
- ✅ Адаптивный дизайн (Media Queries)
- ✅ Препроцессоры: LESS, SCSS
- ✅ CSS-переменные
- ✅ Псевдоклассы и псевдоэлементы

### Методология БЭМ
```css
/* Пример структуры БЭМ */
.card { }
.card__header { }
.card__title { }
.card__body { }
.card--highlighted { }
```

## 💻 JavaScript

### Основы
- ✅ ES6+ синтаксис (let, const, arrow functions)
- ✅ Работа с DOM
- ✅ События и обработчики
- ✅ Асинхронность (Promises, async/await)
- ✅ Fetch API для работы с данными

### jQuery
- ✅ Селекторы и манипуляция DOM
- ✅ Эффекты и анимации
- ✅ AJAX-запросы
- ✅ Обработка событий

### React (базовый уровень)
```javascript
// Функциональные компоненты
const Component = () => {
  const [state, setState] = useState(initialValue);
  
  useEffect(() => {
    // side effects
  }, [dependencies]);
  
  return <div>...</div>;
};

// Работа с классовыми компонентами
class Component extends React.Component {
  render() {
    return <div>...</div>;
  }
}
```

## 🎨 Дизайн инструменты

### Figma
- ✅ Экспорт стилей и ассетов
- ✅ Работа с компонентами
- ✅ Понимание Auto Layout
- ✅ Измерение размеров и отступов
- ✅ Экспорт SVG и растровой графики

## 🔧 Инструменты разработки

### Git
```bash
# Базовые команды
git init
git add .
git commit -m "message"
git push origin main
git pull
git branch feature-name
git merge feature-name
```

### Bootstrap
- ✅ Сетка (Grid System)
- ✅ Компоненты (кнопки, формы, карточки)
- ✅ Утилиты (spacing, display, colors)
- ✅ Кастомизация через SCSS
- ✅ Работа с Bootstrap 3 и 4

## 🌐 CMS

### WordPress
- ✅ Создание и настройка тем
- ✅ Работа с шаблонами страниц
- ✅ Кастомные поля (ACF)
- ✅ Хуки и фильтры
- ✅ Оптимизация производительности

## 📚 Изучаю сейчас

### Gulp
```javascript
// Пример задачи Gulp
gulp.task('sass', function() {
  return gulp.src('src/scss/**/*.scss')
    .pipe(sass())
    .pipe(gulp.dest('dist/css'));
});
```

### Webpack
```javascript
// Базовая конфигурация
module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'bundle.js',
    path: path.resolve(__dirname, 'dist')
  }
};
```

### Шаблонизаторы
- 📖 Smarty — изучаю синтаксис и логику работы
- 📖 Blade — знакомлюсь с директивами и компонентами

### Email-верстка
- 📖 Особенности верстки для почтовых клиентов
- 📖 Табличная верстка
- 📖 Inline-стили
- 📖 Тестирование в разных клиентах

## 🎯 Опыт работы

### Типичные задачи, которые решаю:

1. **Landing Page**
   - Верстка по Figma-макету
   - Адаптив для всех устройств
   - Анимации и интерактивность
   - Оптимизация производительности

2. **Многостраничные сайты**
   - Создание компонентной структуры
   - Единый стиль и UI-kit
   - SEO-оптимизация
   - Кроссбраузерность


## 📊 Показатели качества кода

- ✅ **Валидность:** HTML и CSS проходят валидацию W3C
- ✅ **Производительность:** PageSpeed Insights > 90
- ✅ **Доступность:** Lighthouse Accessibility > 90
- ✅ **Кроссбраузерность:** Тестирование в Chrome, Firefox, Safari, Edge
- ✅ **Адаптивность:** Проверка на устройствах от 320px до 4K

## 🔍 Чек-лист проверки работы

Перед сдачей задачи я проверяю:

- [ ] Соответствие макету (pixel-perfect)
- [ ] Адаптивность на всех брейкпоинтах
- [ ] Кроссбраузерность
- [ ] Валидность HTML/CSS
- [ ] Оптимизация изображений
- [ ] Производительность загрузки
- [ ] Accessibility
- [ ] Семантичность кода
- [ ] Чистота кода (БЭМ, форматирование)
- [ ] Отсутствие console.log и debug-кода

---

💡 **Постоянно развиваюсь и изучаю новое!**

# Лабораторная работа №1. Введение в HTML

## Задание 1
Создать страницу по примеру, используя тег для абзаца и тег strong.
### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
    <p>I am learning <strong>HTML</strong> and <strong>CSS</strong>!</p>
</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/14fcf079-1f7a-4146-a06b-45fa5daf2a49)

## Задание 2
Создать страницу по примеру. Требования:
- Изменить название документа на «Абзацы»;
- Используйте тег h1 для заголовка;
- Используйте p-теги для каждой строки текста;
- Смотрите скриншот и используйте теги strong и em там, где это необходимо.

### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Абзацы</title>
</head>
<body>
    <h1>Top Tips for Effective Presentations</h1>

    <p>This page draws on published advice from expert presenters around the world, which will help to take your presentations from merely <strong>good</strong> to <strong>great</strong>.</p>

    <p>By bringing together advice from a wide range of people, the aim is to cover a whole range of areas.</p>

    <p>Whether you are an experienced presenter, or just starting out, there should be ideas here to help you to <strong>improve</strong>.</p>

    <p><strong>It’s hard to be relaxed and be yourself when you’re nervous.</strong></p>

    <p>But time and again, the great presenters say that the most important thing is to connect with your audience, and the best way to do that is to let your passion for the subject shine through.</p>

    <p><em>Be honest with the audience about what is important to you and why it matters.</em></p>

    <p><strong>Your presentation needs to be built around what your audience is going to get out of the presentation.</strong></p>

    <p>As you prepare the presentation, you always need to bear in mind what the audience needs and wants to know, not what you can tell them.</p>

    <p><em>While you’re giving the presentation, you also need to remain focused on your audience’s response, and react to that.</em></p>

    <p>For more ideas, see our page on Coping with Presentation Nerves.</p>

    <p><strong>Author: <em>Jhon Devis</em></strong></p>

</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/4faf2f5b-cf42-48e8-979c-ea7c31fbabb9)

## Задание 3
Создать страницу по примеру. Требования:
- Изменить название документа на «Single Article Page».
- Создайте статью с несколькими элементами внутри
- Используйте теги h2 и h4 для заголовков
- Используйте p теги для текста
- Используйте тег img для изображения

### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Single Article Page</title>
</head>
<body>
<article>
    <h2>Egyptian Mau</h2>
    <h4>Egyptian Maus are a small- to medium-sized short-haired cat breed.</h4>
    <p>Along with the Bahraini Dilmun cat, they are one of the few naturally spotted breeds of domesticated cat. The spots of the Mau occur on only the tips of the hairs of its coat. It is considered to be a rare breed.</p>
    <p>The breed conformation is described as "a balance between the compactness of a Burmese and the slim elegance of a Siamese. Its medium-length body is muscular, with the hind legs longer than the front, giving the Mau the appearance of standing on tiptoes when upright."</p>
    <img src="cat.jpg" width="500" alt="Egyptian Mau Photo">
</article>

</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/b3ebdca0-81bd-48b3-9d31-06d9b1530ee1)

## Задание 4
Создать страницу по примеру. Требования:
- Измените название документа на Lists;
- Добавить раздел с двумя статьями внутри (для каждого списка);
- Каждая статья должна иметь заголовок h2 (Используйте ul для неупорядоченного списка);
- Добавьте четыре элемента списка (Используйте  ol  reversed  для  упорядоченного  реверсированного списка);
- Добавьте три элемента списка.

### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lists</title>
</head>
<body>
<div>
    <article>
        <h2>HTML Unordered list</h2>
        <ul>
            <li>Hyper is the opposite of linear. It used to be that computer programs had to move in a linear fashion. This before this, this before this, and so on. HTML does not hold to that pattern and allows the person viewing the World Wide Web page to go anywhere, any time they want.</li>

            <li>Text is what you will use. Real, honest to goodness English letters.</li>

            <li>Mark up is what you will do. You will write in plain English and then mark up what you wrote. More to come on that in the next Primer.</li>

            <li>Language because they needed something that started with "L" to finish HTML and Hypertext Markup Louie didn't flow correctly. Because it's a language, really—but the language is plain English.</li>
        </ul>
    </article>
    <article>
        <h2>Reversed list</h2>
        <ol reversed>
            <li>Alt-text is not a description of an image, but a replacement for the image in case it is not displayed.</li>
            <li>An ampersand character “&” must always be escaped like this: “&” – even in URLs.</li>
            <li>Most presentation-based HTML tags are deprecated in recent versions of HTML.</li>
        </ol>
    </article>
</div>

</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/9f5d9221-7a78-4e26-b8d0-3b84b81fc1f4)

## Задание 5
Создать страницу по примеру. Требования:
- Измените название документа на Nested Lists;
- Используйте тег h2 для заголовка;
- Используйте различные типы для упорядоченных и неупорядоченных списков (Смотрите скриншот и используйте различные атрибуты типа, такие как circle, disc и т.д.)

### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Nested Lists</title>
</head>
<body>
<article>
    <h2>Nested List</h2>
    <ol type="I">
        <li>HTML5</li>
        <ol type="a">
            <li>markup language</li>
            <li>used for structuring and presenting content on the World Wide Web</li>
        </ol>
        <li>HTML Versions</li>
        <ol>
            <li>Development</li>
            <li>HTML versions timeline</li>
            <ul type="circle">
                <li>HTML draft version timeline</li>
                <li>XHTML versions</li>
            </ul>
            <li>Markup</li>
        </ol>
        <li>HTML5 Semantic Tags</li>
        <ul type="disc">
            <li>article</li>
            <li>aside</li>
            <li>details</li>
            <li>figcaption</li>
            <li>figure</li>
            <li>footer</li>
            <li>header</li>
            <li>main</li>
            <li>mark</li>
            <li>nav</li>
            <li>section</li>
            <li>summary</li>
            <li>time</li>
        </ul>
    </ol>
</article>
</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/a2f96cdc-9cbc-4277-852a-d29df0aa9b3b)

## Задание 6
Создать страницу по примеру. Требования:
- Изменить название документа на Tables;
- Используйте тег h2 для заголовка;
- Используйте тег table для создания таблицы;
- Используйте тег tr для строк;
- Используйте теги th и td для столбцов;
- Используйте тег span со значением checked для проверенных элементов.
### Код страницы
`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tables</title>
</head>
<body>
<h2>HTML Table</h2>
<table>
    <tr>
        <th>Name</th><th>Self-Employed</th><th>Country</th>
    </tr>
    <tr>
        <td>Alfreds Futterkiste</td><td><span>checked</span></td><td>Germany</td>
    </tr>
    <tr>
        <td>Centro comercial Moctezuma</td><td></td><td>Mexico</td>
    </tr>
    <tr>
        <td>Ernst Handel</td><td></td><td>Austria</td>
    </tr>
    <tr>
        <td>Island Trading</td><td><span>checked</span></td><td>UK</td>
    </tr>
    <tr>
        <td>Laughing Bacchus Winecellars</td><td><span>checked</span>></td><td>Canada</td>
    </tr>
    <tr>
        <td>Magazzini Alimentari Riuniti</td><td></td><td>Italy</td>
    </tr>
</table>
</body>
</html>`

### Демонстрация работы
![image](https://github.com/user-attachments/assets/a43515b4-cf18-4ec6-8fe1-3bb9ee75c5ad)

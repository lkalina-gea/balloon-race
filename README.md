# balloon-race

A static webpage to track donation amounts in an office donation competition. In our case, the manager whose employees donated the most "won" a pie in the face.

## Setup

Place the managers' headshot picutures and a logo image in images/. 

Update manager names, donation amounts, and headshot image paths in index.html:

```javascript
    // Define manager data (name, donation, and headshot image path)
    const managerData = [
      { name: 'Jim', donation: 1200, image: 'images/Jim.jpg' },
      { name: 'Jenn', donation: 800, image: 'images/Jenn.jpg' },
      { name: 'Adam', donation: 1500, image: 'images/Adam.jpg' },
      { name: 'David', donation: 0, image: 'images/David.jpg' },
      { name: 'Melinda', donation: 0, image: 'images/Melinda.jpg' },
      // Additional manager placeholders
      { name: 'Manager 6', donation: 1000, image: 'images/manager.png' },
      { name: 'Manager 7', donation: 1000, image: 'images/manager.png' },
      { name: 'Manager 8', donation: 1000, image: 'images/manager.png' }
    ];
```

Update the logo, title, and subtitle:
```html
<img src="images/pie.png" alt="Pie" class="img-fluid">
      </div>
      <div class="col">
        <h1><b>Logistics Balloon Race Tracker</b></h1>
        <p>Vote for a leader to win by donating (here)! The leader with the highest donations will "win" a pie in the face on (date). All donations go to (charity). This tracker will be updated (frequency).</p>
```

Host the webpage with [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) or similar.


    

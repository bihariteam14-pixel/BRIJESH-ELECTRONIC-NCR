<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Brijesh Electronic & Social</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* --- GENERAL --- */
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: #f0f2f5; padding-bottom: 70px; user-select: none; }
        
        /* HEADER */
        .site-header { background: #1a237e; color: white; padding: 12px 15px; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.2); }
        .header-icons i { font-size: 1.3em; margin-left: 15px; cursor: pointer; }

        /* MENU */
        .dropdown-menu { display: none; position: absolute; top: 50px; right: 10px; background: white; width: 220px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); border-radius: 5px; z-index: 2000; }
        .dropdown-menu.show { display: block; }
        .dropdown-menu a { display: block; padding: 12px; border-bottom: 1px solid #eee; text-decoration: none; color: #333; font-weight: bold; cursor: pointer; }

        /* SECTIONS */
        .page-section { display: none; padding: 10px; }
        .page-section.active { display: block; }

        /* --- SHOP UI --- */
        .shop-grid { display: grid; gap: 20px; }
        .shop-card { background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        .shop-card img { width: 100%; height: 200px; object-fit: cover; }
        .shop-details { padding: 15px; }
        .shop-details h2 { color: #007bff; font-size: 1.5em; margin: 0 0 10px 0; }
        .problem-list { list-style: none; padding: 0; margin: 10px 0; text-align: left; }
        .problem-list li { padding: 5px 0; border-bottom: 1px dashed #eee; font-size: 0.95em; color: #555; display: flex; }
        .problem-list li:before { content: '👉'; margin-right: 8px; }
        .shop-btn { width: 100%; background: #28a745; color: white; padding: 12px; border: none; border-radius: 5px; font-weight: bold; margin-top: 10px; font-size: 1em; }

        /* --- SOCIAL UI --- */
        .stories-wrapper { display: flex; gap: 10px; overflow-x: auto; padding: 10px; background: white; margin-bottom: 10px; border-radius: 8px; }
        .story-item { min-width: 80px; height: 140px; border-radius: 10px; position: relative; overflow: hidden; background: #000; border: 2px solid #1a237e; flex-shrink: 0; }
        .story-item img { width: 100%; height: 100%; object-fit: cover; }
        .story-item p { position: absolute; bottom: 5px; width: 100%; text-align: center; color: white; font-size: 10px; font-weight: bold; margin: 0; text-shadow: 1px 1px 2px black; }
        .story-add { background: white; border: 2px dashed #ccc; display: flex; align-items: center; justify-content: center; flex-direction: column; }
        
        .create-post { background: white; padding: 15px; display: flex; gap: 10px; align-items: center; border-radius: 8px; margin-bottom: 15px; }
        .user-dp { width: 40px; height: 40px; border-radius: 50%; object-fit: cover; border: 1px solid #ddd; }
        .post-card { background: white; margin-bottom: 15px; border-radius: 8px; padding-bottom: 5px; }
        .post-header { padding: 10px; display: flex; align-items: center; gap: 10px; }
        .post-media { width: 100%; max-height: 400px; object-fit: contain; background: black; }
        .post-actions { display: flex; justify-content: space-around; padding: 10px; border-top: 1px solid #eee; }
        .act-btn { background: none; border: none; font-weight: bold; color: #555; display: flex; align-items: center; gap: 5px; font-size: 14px; cursor: pointer; }

        /* --- MODALS --- */
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.8); z-index: 5000; justify-content: center; align-items: center; }
        .modal-content { background: white; padding: 20px; width: 95%; max-width: 400px; border-radius: 10px; position: relative; max-height: 90vh; overflow-y: auto; }
        .close-btn { position: absolute; top: 10px; right: 15px; font-size: 24px; cursor: pointer; z-index: 10; }
        .full-btn { width: 100%; padding: 12px; border: none; border-radius: 5px; font-weight: bold; margin-top: 10px; color: white; cursor: pointer;}
        .inp { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; box-sizing: border-box; }

        /* MUSIC */
        #musicResults { max-height: 200px; overflow-y: auto; margin-top: 10px; border: 1px solid #eee; }
        .song-item { display: flex; align-items: center; padding: 8px; border-bottom: 1px solid #eee; cursor: pointer; }
        .song-item img { width: 40px; height: 40px; border-radius: 4px; margin-right: 10px; }

        /* STORY VIEWER */
        #storyViewer { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: black; z-index: 6000; flex-direction: column; }
        .progress-container { width: 98%; height: 3px; background: #555; margin: 5px auto; border-radius: 2px; display: flex; }
        .progress-bar { height: 100%; background: white; width: 0%; }
        .sv-header { display: flex; align-items: center; padding: 10px; gap: 10px; color: white; position: absolute; top: 20px; width: 100%; z-index: 2; }

        /* BOTTOM NAV */
        .bottom-nav { position: fixed; bottom: 0; width: 100%; background: white; border-top: 1px solid #ddd; display: flex; justify-content: space-around; padding: 12px 0; z-index: 4000; }
        .nav-icon { font-size: 22px; color: #666; cursor: pointer; }
        .nav-icon.active { color: #1a237e; }
    </style>
</head>
<body>

    <div class="site-header">
        <h1 id="appTitle">Brijesh Electronic</h1>
        <div class="header-icons"><i class="fas fa-bars" onclick="toggleMenu()"></i></div>
    </div>

    <div id="shopView" class="page-section active">
        <div class="shop-grid">
            <div class="shop-card">
                <img src="https://via.placeholder.com/400x200?text=TV+Repair">
                <div class="shop-details">
                    <h2>📺 TV Repair Service</h2>
                    <ul class="problem-list">
                        <li>Screen Tooti Ya Line Aa Rahi Hai</li>
                        <li>TV Bilkul On Nahi Ho Raha Hai</li>
                        <li>Aawaaz Aa Rahi Hai Par Picture Nahi Hai</li>
                        <li>Bar-Bar Apne Aap Band Ho Jata Hai</li>
                        <li>HDMI/USB Port Kaam Nahi Kar Raha Hai</li>
                    </ul>
                    <button class="shop-btn" onclick="openOrder('TV Repair')">Order Now</button>
                </div>
            </div>
            <div class="shop-card">
                <img src="https://via.placeholder.com/400x200?text=Washing+Machine">
                <div class="shop-details">
                    <h2>🧺 Washing Machine Repair</h2>
                    <ul class="problem-list">
                        <li>Kapde Dry (Spin) Nahi Ho Rahe Hain</li>
                        <li>Motor Bilkul Nahi Chal Rahi Hai</li>
                        <li>Paani Drain (Nikal) Nahi Ho Raha Hai</li>
                        <li>Bahut Zyaada Aawaaz Karti Hai</li>
                        <li>Door Ya Lock Kaam Nahi Kar Raha Hai</li>
                    </ul>
                    <button class="shop-btn" onclick="openOrder('Washing Machine')">Order Now</button>
                </div>
            </div>
            <div class="shop-card">
                <img src="https://via.placeholder.com/400x200?text=Dish+Antenna">
                <div class="shop-details">
                    <h2>📡 Dish/DTH Service</h2>
                    <ul class="problem-list">
                        <li>Naya Dish Antenna Lagwana Hai</li>
                        <li>Signal Nahi Aa Raha</li>
                        <li>Antenna Hawa Se Hil Gaya Hai</li>
                        <li>LNB Ya Wire Badlav Ki Zaroorat Hai</li>
                        <li>Setup Box Mein Channel Nahi Aa Rahe Hain</li>
                    </ul>
                    <button class="shop-btn" onclick="openOrder('Dish Antenna')">Order Now</button>
                </div>
            </div>
            <div class="shop-card">
                <img src="https://via.placeholder.com/400x200?text=Cable+Fixing">
                <div class="shop-details">
                    <h2>🔌 Cable Fixing</h2>
                    <ul class="problem-list">
                        <li>Naye TV mein Data Cable Lagwana Hai</li>
                        <li>TV Aur Setup Box Ko Connect Karna Hai</li>
                        <li>TV Picture/Sound Saaf Nahi Aa Raha Hai</li>
                        <li>Purani Cable Ya Connector Badlav Ki Zaroorat Hai</li>
                        <li>Setup Box On Nahi Ho Raha Hai</li>
                    </ul>
                    <button class="shop-btn" onclick="openOrder('Cable Fixing')">Order Now</button>
                </div>
            </div>
        </div>
    </div>

    <div id="socialView" class="page-section">
        <div class="stories-wrapper" id="storyTray">
            <div class="story-item story-add" onclick="openModal('storyUploadModal')">
                <i class="fas fa-plus-circle" style="font-size:30px; color:#1a237e;"></i>
                <p style="color:#333;">Add Story</p>
            </div>
        </div>
        <div class="create-post" onclick="openModal('postModal')">
            <img src="https://via.placeholder.com/50" class="user-dp global-pic">
            <div style="flex:1; background:#f0f2f5; padding:10px; border-radius:20px; color:#666;">What's on your mind?</div>
        </div>
        <div id="feedContainer"></div>
    </div>

    <div id="adminView" class="page-section">
        <div style="display:flex; justify-content:space-between; align-items:center;">
            <h2>🔑 Admin Orders</h2>
            <i class="fas fa-times-circle" style="color:red; font-size:30px; cursor:pointer;" onclick="switchTab('shop')"></i>
        </div>
        <div id="orderList"></div>
        <button onclick="localStorage.removeItem('orders'); loadAdmin();" style="width:100%; margin-top:20px; background:red; color:white; padding:10px; border:none;">Clear All</button>
    </div>

    <div id="profileView" class="page-section" style="text-align:center;">
        <div style="position:relative; display:inline-block; margin-top:20px;">
            <img src="https://via.placeholder.com/120" id="profileDp" class="global-pic" style="width:120px; height:120px; border-radius:50%; border:3px solid #1a237e; object-fit:cover;">
            <label for="picInp" style="position:absolute; bottom:0; right:0; background:#1a237e; color:white; padding:8px; border-radius:50%; cursor:pointer;"><i class="fas fa-camera"></i></label>
            <input type="file" id="picInp" hidden accept="image/*" onchange="changePic(this)">
        </div>
        <h2 id="profileNameDisplay">Guest</h2>
        <div style="padding:20px;">
            <input type="text" id="nameInp" class="inp" placeholder="Enter New Name">
            <button class="full-btn" style="background:#1a237e;" onclick="saveName()">Save Name</button>
        </div>
    </div>

    <div class="bottom-nav">
        <i class="fas fa-store nav-icon active" id="navShop" onclick="switchTab('shop')"></i>
        <i class="fas fa-users nav-icon" id="navSocial" onclick="switchTab('social')"></i>
        <i class="fas fa-user-circle nav-icon" id="navProfile" onclick="switchTab('profile')"></i>
    </div>

    <div id="mainMenu" class="dropdown-menu">
        <a onclick="switchTab('shop')">🏠 Shop</a>
        <a onclick="switchTab('social')">👥 Social</a>
        <a onclick="switchTab('profile')">👤 Profile</a>
        <a onclick="checkAdmin()">🔑 Admin Panel</a>
    </div>

    <div id="storyUploadModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('storyUploadModal')">&times;</span>
            <h3>Add Story</h3>
            <input type="file" id="storyFile" accept="image/*" onchange="previewStory(this)">
            <input type="text" id="musicQuery" class="inp" placeholder="Search Song...">
            <button class="full-btn" style="background:#1a237e;" onclick="searchMusic()">Search Music</button>
            <div id="musicResults"></div>
            <button class="full-btn" style="background:#1877F2;" onclick="publishStory()">Share Story</button>
        </div>
    </div>

    <div id="postModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('postModal')">&times;</span>
            <h3>Create Post</h3>
            <textarea id="pText" class="inp" style="height:80px;" placeholder="What's up?"></textarea>
            <input type="file" id="pFile" accept="image/*,video/*" onchange="previewPost(this)">
            <div id="pPreview"></div>
            <button class="full-btn" style="background:#1877F2;" onclick="publishPost()">Post</button>
        </div>
    </div>

    <div id="orderModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('orderModal')">&times;</span>
            <h3 id="orderTitle">Booking</h3>
            <select id="problemSelect" class="inp"></select>
            <input type="text" id="orderName" class="inp" placeholder="Name">
            <input type="tel" id="orderPhone" class="inp" placeholder="Phone">
            <textarea id="orderAddr" class="inp" placeholder="Address"></textarea>
            <button class="full-btn" style="background:#28a745;" onclick="confirmOrder()">Confirm</button>
        </div>
    </div>

    <div id="storyViewer">
        <div class="progress-container"><div class="progress-bar" id="storyProgress"></div></div>
        <div class="sv-header">
            <img src="" class="global-pic" style="width:30px; height:30px; border-radius:50%;">
            <span id="svUser" style="color:white; font-weight:bold;">User</span>
            <span class="close-btn" style="color:white; position:static; margin-left:auto;" onclick="closeViewer()">&times;</span>
        </div>
        <img id="viewImg" style="width:100%; height:100%; object-fit:contain;">
        <audio id="viewAudio"></audio>
    </div>

    <script>
        let userData = JSON.parse(localStorage.getItem('user_data')) || { name: "Guest", pic: "https://via.placeholder.com/150" };
        let stories = JSON.parse(localStorage.getItem('stories') || '[]');
        let posts = JSON.parse(localStorage.getItem('posts') || '[]');
        let mediaBuffer, selectedSong, timer;

        const probsDB = {
            'TV Repair': ['Screen Line','Dead','No Sound','HDMI Issue'],
            'Washing Machine': ['No Spin','Motor Dead','Water Leak','Noise'],
            'Dish Antenna': ['Signal Issue','New Fitting','Wire Cut'],
            'Cable Fixing': ['Setup Box Issue','Wire Problem','No Signal']
        };

        window.onload = () => { applyUser(); loadStories(); loadPosts(); };

        function applyUser() {
            document.querySelectorAll('.global-pic').forEach(img => img.src = userData.pic);
            document.getElementById('profileNameDisplay').innerText = userData.name;
        }

        // --- PROFILE FUNCTIONS ---
        function changePic(input) {
            if(input.files[0]) {
                let r = new FileReader();
                r.onload = e => { userData.pic = e.target.result; saveUser(); };
                r.readAsDataURL(input.files[0]);
            }
        }
        function saveName() {
            let n = document.getElementById('nameInp').value;
            if(n) { userData.name = n; saveUser(); alert("Name Saved!"); }
        }
        function saveUser() { localStorage.setItem('user_data', JSON.stringify(userData)); applyUser(); }

        // --- NAVIGATION ---
        function switchTab(id) {
            document.querySelectorAll('.page-section').forEach(p => p.classList.remove('active'));
            document.querySelectorAll('.nav-icon').forEach(n => n.classList.remove('active'));
            document.getElementById(id+'View').classList.add('active');
            if(document.getElementById('nav'+id.charAt(0).toUpperCase()+id.slice(1)))
                document.getElementById('nav'+id.charAt(0).toUpperCase()+id.slice(1)).classList.add('active');
            document.getElementById('mainMenu').classList.remove('show');
        }
        function toggleMenu() { document.getElementById('mainMenu').classList.toggle('show'); }
        function openModal(id) { document.getElementById(id).style.display = 'flex'; }
        function closeModal(id) { document.getElementById(id).style.display = 'none'; }

        // --- SHOP & ADMIN ---
        function openOrder(svc) {
            currentSvc = svc; document.getElementById('orderTitle').innerText = svc;
            let sel = document.getElementById('problemSelect'); sel.innerHTML = "";
            (probsDB[svc] || ['Other']).forEach(p => sel.innerHTML += `<option>${p}</option>`);
            openModal('orderModal');
        }
        function confirmOrder() {
            let o = { svc: currentSvc, name: document.getElementById('orderName').value, phone: document.getElementById('orderPhone').value, addr: document.getElementById('orderAddr').value, date: new Date().toLocaleString() };
            let orders = JSON.parse(localStorage.getItem('orders') || '[]');
            orders.push(o); localStorage.setItem('orders', JSON.stringify(orders));
            closeModal('orderModal'); alert("Order Success!");
        }
        function checkAdmin() { if(prompt("Pass:")==="12345") { loadAdmin(); switchTab('admin'); } else alert("Wrong!"); }
        function loadAdmin() {
            let orders = JSON.parse(localStorage.getItem('orders') || '[]');
            document.getElementById('orderList').innerHTML = orders.map(o => `<div style="padding:10px; border-bottom:1px solid #ccc;"><b>${o.svc}</b> - ${o.name} (${o.phone})</div>`).join('') || "No Orders";
        }

        // --- SOCIAL ---
        async function searchMusic() {
            let q = document.getElementById('musicQuery').value;
            let res = await fetch(`https://itunes.apple.com/search?term=${q}&limit=5`);
            let data = await res.json();
            document.getElementById('musicResults').innerHTML = data.results.map(s => `<div class="song-item" onclick="selectedSong='${s.previewUrl}'; alert('Song Selected')"><img src="${s.artworkUrl60}"> ${s.trackName}</div>`).join('');
        }
        function previewStory(i) { let r = new FileReader(); r.onload = e => mediaBuffer = e.target.result; r.readAsDataURL(i.files[0]); }
        function publishStory() {
            stories.unshift({ img: mediaBuffer, music: selectedSong, user: userData.name });
            localStorage.setItem('stories', JSON.stringify(stories));
            closeModal('storyUploadModal'); loadStories();
        }
        function loadStories() {
            let tray = document.getElementById('storyTray');
            tray.innerHTML = `<div class="story-item story-add" onclick="openModal('storyUploadModal')"><i class="fas fa-plus-circle"></i></div>` + 
            stories.map((s,i) => `<div class="story-item" onclick="viewStory(${i})"><img src="${s.img}"><p>${s.user}</p></div>`).join('');
        }
        function viewStory(i) {
            let s = stories[i]; document.getElementById('storyViewer').style.display = 'flex';
            document.getElementById('viewImg').src = s.img; document.getElementById('svUser').innerText = s.user;
            let a = document.getElementById('viewAudio'); if(s.music) { a.src=s.music; a.play(); }
            let bar = document.getElementById('storyProgress'); let w=0;
            timer = setInterval(() => { w++; bar.style.width=w+'%'; if(w>=100) closeViewer(); }, 50);
        }
        function closeViewer() { document.getElementById('storyViewer').style.display='none'; document.getElementById('viewAudio').pause(); clearInterval(timer); }

        function previewPost(i) { let r = new FileReader(); r.onload = e => mediaBuffer = e.target.result; r.readAsDataURL(i.files[0]); }
        function publishPost() {
            posts.unshift({ user: userData.name, pic: userData.pic, text: document.getElementById('pText').value, img: mediaBuffer });
            localStorage.setItem('posts', JSON.stringify(posts));
            closeModal('postModal'); loadPosts();
        }
        function loadPosts() {
            document.getElementById('feedContainer').innerHTML = posts.map(p => `<div class="post-card"><div class="post-header"><img src="${p.pic}" class="user-dp"><b>${p.user}</b></div><div style="padding:10px;">${p.text}</div>${p.img ? `<img src="${p.img}" class="post-media">` : ''}</div>`).join('');
        }
    </script>
</body>
</html>

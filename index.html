<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🔍 Admin Checker - Free Tool</title>
    <meta name="description" content="Check if email/username is admin instantly!">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            color: #333;
        }
        .container {
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(20px);
            border-radius: 24px;
            padding: 50px 40px;
            max-width: 500px;
            width: 100%;
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
            text-align: center;
            border: 1px solid rgba(255,255,255,0.2);
        }
        .logo {
            font-size: 2.5em;
            background: linear-gradient(45deg, #667eea, #764ba2, #f093fb);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 10px;
            font-weight: 700;
        }
        .subtitle {
            color: #666;
            margin-bottom: 35px;
            font-size: 1.1em;
        }
        input {
            width: 100%;
            padding: 18px 20px;
            font-size: 18px;
            border: 3px solid #e1e5e9;
            border-radius: 16px;
            margin-bottom: 25px;
            transition: all 0.3s ease;
            background: white;
        }
        input:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 4px rgba(102, 126, 234, 0.15);
            transform: translateY(-2px);
        }
        input::placeholder {
            color: #999;
            font-weight: 500;
        }
        button {
            width: 100%;
            padding: 18px;
            font-size: 18px;
            font-weight: 600;
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            border: none;
            border-radius: 16px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 30px rgba(102, 126, 234, 0.4);
        }
        button:active {
            transform: translateY(-1px);
        }
        .result {
            margin-top: 30px;
            padding: 25px;
            border-radius: 16px;
            font-size: 20px;
            font-weight: 700;
            display: none;
            animation: slideIn 0.4s ease;
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .admin {
            background: linear-gradient(45deg, #d4edda, #c3e6cb);
            color: #155724;
            border: 3px solid #28a745;
        }
        .not-admin {
            background: linear-gradient(45deg, #f8d7da, #f5c6cb);
            color: #721c24;
            border: 3px solid #dc3545;
        }
        .loading {
            display: none;
            color: #667eea;
            font-size: 16px;
            margin-top: 10px;
        }
        .footer {
            margin-top: 40px;
            color: #888;
            font-size: 14px;
        }
        @media (max-width: 480px) {
            .container { padding: 40px 25px; margin: 10px; }
            .logo { font-size: 2em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">🔍 Admin Checker</div>
        <div class="subtitle">Enter email/username to check admin status instantly</div>
        
        <input type="text" id="input" placeholder="admin@example.com or username..." maxlength="100">
        <div class="loading" id="loading">🔄 Checking...</div>
        <button onclick="checkAdmin()">🔍 Check Now</button>
        
        <div id="result" class="result"></div>
        
        <div class="footer">
            ✅ 100% Free • No login required • Instant results
        </div>
    </div>

    <script>
        function checkAdmin() {
            const input = document.getElementById('input').value.trim();
            const result = document.getElementById('result');
            const loading = document.getElementById('loading');
            const btn = event.target;
            
            if (!input) {
                showResult('⚠️ Please enter an email or username!', 'not-admin');
                return;
            }
            
            // Show loading
            loading.style.display = 'block';
            btn.textContent = 'Checking...';
            btn.disabled = true;
            result.style.display = 'none';
            
            // Simulate API delay (remove for instant)
            setTimeout(() => {
                loading.style.display = 'none';
                btn.textContent = '🔍 Check Now';
                btn.disabled = false;
                
                const cleanInput = input.toLowerCase();
                
                // 🔥 CUSTOMIZE THESE ADMIN KEYWORDS
                const adminKeywords = [
                    'admin', 'administrator', 'root', 'super', 'superadmin',
                    'owner', 'mod', 'moderator', 'dev', 'developer',
                    'support', 'staff', 'team', 'founder', 'ceo'
                ];
                
                // Domain-based checks
                const adminDomains = ['admin.com', 'root.net', 'super.org'];
                
                const isAdminKeyword = adminKeywords.some(keyword => 
                    cleanInput.includes(keyword)
                );
                
                const isAdminDomain = adminDomains.some(domain => 
                    cleanInput.includes(domain)
                );
                
                const isAdmin = isAdminKeyword || isAdminDomain;
                
                if (isAdmin) {
                    showResult('✅ YES! This is an ADMIN account!', 'admin');
                } else {
                    showResult('❌ Not detected as admin account.', 'not-admin');
                }
            }, 1200);
        }
        
        function showResult(message, type) {
            const result = document.getElementById('result');
            result.textContent = message;
            result.className = `result ${type}`;
            result.style.display = 'block';
            result.scrollIntoView({ behavior: 'smooth' });
        }
        
        // Enter key support
        document.getElementById('input').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') checkAdmin();
        });
        
        // Auto-focus input
        document.getElementById('input').focus();
    </script>
</body>
</html>

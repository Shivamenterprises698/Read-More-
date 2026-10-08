<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivam Enterprises</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, sans-serif; }
        body { background: #f4f6f9; color: #333; line-height: 1.4; padding: 10px; }
        header { text-align: center; padding: 20px 10px; background: #1e3a8a; color: white; border-radius: 8px; margin-bottom: 15px; }
        header h1 { font-size: 24px; margin-bottom: 5px; }
        header p { font-size: 14px; opacity: 0.9; }
        
        .btn-group { display: flex; gap: 10px; justify-content: center; margin-top: 15px; }
        .btn { padding: 8px 16px; border-radius: 5px; text-decoration: none; font-weight: bold; font-size: 14px; color: white; display: inline-flex; align-items: center; gap: 5px; }
        .btn-call { background: #2563eb; }
        .btn-wa { background: #16a34a; }
        
        section { background: white; padding: 15px; border-radius: 8px; margin-bottom: 15px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        section h2 { font-size: 18px; color: #1e3a8a; border-bottom: 2px solid #e5e7eb; padding-bottom: 5px; margin-bottom: 15px; text-align: center; }
        
        .grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; }
        .card { background: #f8fafc; border: 1px solid #e2e8f0; padding: 12px 8px; border-radius: 6px; text-align: center; }
        .card .icon { font-size: 24px; margin-bottom: 5px; }
        .card h3 { font-size: 14px; color: #1e3a8a; margin-bottom: 4px; }
        .card p { font-size: 12px; color: #64748b; }
        
        .features { list-style: none; }
        .features li { font-size: 13px; margin-bottom: 8px; padding-left: 20px; position: relative; }
        .features li::before { content: "✓"; position: absolute; left: 0; color: #16a34a; font-weight: bold; }
        
        .contact-info { text-align: center; font-size: 13px; color: #475569; }
        .contact-info p { margin: 5px 0; }
        footer { text-align: center; font-size: 11px; color: #94a3b8; padding: 10px 0; }
    </style>
</head>
<body>

    <header>
        <h1>Shivam Enterprises</h1>
        <p>Cement • Gitti • Balu • Tractor Service</p>
        <p style="font-size: 12px; margin-top: 5px;">निर्माण सामग्री और ट्रैक्टर सेवा के लिए संपर्क करें।</p>
        <div class="btn-group">
            <a href="tel:9103453008" class="btn btn-call">📞 Call Now</a>
            <a href="https://wa.me" class="btn btn-wa">💬 WhatsApp</a>
        </div>
    </header>

    <section>
        <h2>हमारी सेवाएँ</h2>
        <div class="grid">
            <div class="card">
                <div class="icon">🧱</div>
                <h3>Cement</h3>
                <p>घर निर्माण के लिए उपलब्ध।</p>
            </div>
            <div class="card">
                <div class="icon">🪨</div>
                <h3>Gitti</h3>
                <p>बेहतरीन क्वालिटी की सप्लाई।</p>
            </div>
            <div class="card">
                <div class="icon">🏖</div>
                <h3>Balu</h3>
                <p>निर्माण कार्य के लिए सप्लाई।</p>
            </div>
            <div class="card">
                <div class="icon">🚜</div>
                <h3>Tractor</h3>
                <p>समय पर बुकिंग सेवा उपलब्ध।</p>
            </div>
        </div>
    </section>

    <section>
        <h2>हमसे क्यों जुड़ें?</h2>
        <ul class="features">
            <li><strong>Material Supply:</strong> सभी प्रकार की निर्माण सामग्री की सही दाम पर सप्लाई।</li>
            <li><strong>Tractor Service:</strong> ट्रैक्टर सेवा के लिए आसान और एडवांस बुकिंग सुविधा।</li>
            <li><strong>आसान संपर्क:</strong> एक क्लिक में सीधे Call या WhatsApp से ऑर्डर की सुविधा।</li>
        </ul>
    </section>

    <section class="contact-info">
        <h2>संपर्क करें</h2>
        <p><strong>📍 पता:</strong> Bandanwar / Pathargama, Godda, Jharkhand</p>
        <p><strong>📞 मोबाइल:</strong> +91 9103453008</p>
        <div class="btn-group" style="margin-top: 10px;">
            <a href="tel:9103453008" class="btn btn-call" style="padding: 6px 12px; font-size: 12px;">📞 Call</a>
            <a href="https://wa.me" class="btn btn-wa" style="padding: 6px 12px; font-size: 12px;">💬 WhatsApp</a>
        </div>
    </section>

    <footer>
        © 2026 Shivam Enterprises. All Rights Reserved.
    </footer>

</body>
</html>

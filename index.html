
<!DOCTYPE html>
<html>
<head>
    <title>IDS Demo</title>
</head>
<body>
    <h2>Demo IDS – Phát hiện tấn công</h2>
    <form id="attackForm">
        <label>Duration:</label><input type="text" name="duration"><br>
        <label>Src Bytes:</label><input type="text" name="src_bytes"><br>
        <label>Dst Bytes:</label><input type="text" name="dst_bytes"><br>
        <button type="submit">Dự đoán</button>
    </form>
    <div id="result"></div>

    <script>
        document.getElementById('attackForm').onsubmit = async (e) => {
            e.preventDefault();
            const form = new FormData(e.target);
            const data = Object.fromEntries(form.entries());
            const res = await fetch('/predict', {
                method: 'POST',
                body: new URLSearchParams(data)
            });
            const result = await res.json();
            document.getElementById('result').innerText = "Kết quả: " + result.kết_quả;
        };
    </script>
</body>
</html>

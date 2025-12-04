# ⚡ Tenant Electricity Bill Calculator

A fair and transparent way to split electricity bills among tenants based on actual appliance usage and hours.

## 📺 Video Tutorial

[![Watch Tutorial] https://youtube.com/shorts/zoR76AAtL1w?si=_3Z7Rh2FIOIzEwLt


## 🌟 Features

- ✅ **Fair Usage Calculation** - Bills calculated based on actual appliance usage
- 📱 **Dropdown Appliance Selection** - Easy selection from common household appliances
- 👥 **Multiple Tenants** - Support for up to 10 tenants
- 💰 **Percentage Breakdown** - See each tenant's usage percentage clearly
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations
- 📊 **Real-time Calculation** - Instant fair share results
- 🏷️ **Tag System** - Visual display of selected appliances with easy removal

## 🚀 Live Demo

[Click here to try it live](https://devteall.github.io/tenant-bill-calculator)

*Replace YOUR_USERNAME with your GitHub username*

## 📖 How It Works

### Step 1: Setup
- Enter your **total electricity bill** amount in Naira (₦)
- Specify the **number of tenants** sharing the apartment

### Step 2: Configure Each Tenant
- Optionally add tenant names
- Select appliances from dropdown menu
- Selected appliances appear as tags (click × to remove)
- Enter average **hours used per day**

### Step 3: Calculate
Click "Calculate Fair Share" to get instant breakdown showing:
- Each tenant's share in Naira
- Percentage of total usage
- Fair distribution based on actual consumption

## 🧮 Calculation Formula

```
Monthly Energy (kWh) = (Total Watts × Hours per Day × 30 Days) ÷ 1000
Tenant's Share (₦) = (Tenant's kWh ÷ Total kWh) × Total Bill Amount
```

## 🛠️ Built With

- **HTML5** - Structure and markup
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - Logic and calculations (no frameworks needed!)

## 💻 Installation & Usage

### Method 1: Use Online
Just visit the [live demo link](https://YOUR_USERNAME.github.io/tenant-bill-calculator) and start using!

### Method 2: Download & Run Locally
1. Download or clone this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/tenant-bill-calculator.git
   ```
2. Open `index.html` in any web browser
3. No installation or dependencies required!

## 📱 Included Appliances

| Appliance | Power Rating |
|-----------|--------------|
| TV | 70W |
| Fan | 60W |
| Freezer | 150W |
| Fridge | 200W |
| AC (1HP) | 900W |
| LED Bulb | 15W |
| Iron | 1000W |
| Laptop | 65W |
| Router | 12W |

*You can easily modify the appliances array in the JavaScript code to add more*

## 💡 Usage Example

**Scenario:**
```
Total Monthly Bill: ₦15,000
Number of Tenants: 3

Tenant 1 (John):
- TV (70W) + Fan (60W)
- 6 hours/day usage
→ Share: ₦1,234 (8.2%)

Tenant 2 (Mary):
- AC 1HP (900W)
- 8 hours/day usage
→ Share: ₦12,960 (86.4%)

Tenant 3 (Paul):
- Laptop (65W) + LED Bulb (15W)
- 4 hours/day usage
→ Share: ₦806 (5.4%)
```

## 🎯 Why Use This Calculator?

✅ **No More Arguments** - Math doesn't lie, fair distribution for everyone  
✅ **Easy to Use** - Simple interface anyone can understand  
✅ **Transparent** - See exactly how calculations are made  
✅ **Mobile Friendly** - Works on phones, tablets, and computers  
✅ **Free & Open Source** - Use it, modify it, share it!

## 🤝 Contributing

Found a bug? Have a feature idea? Contributions are welcome!

1. Fork this repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Make your changes
4. Commit (`git commit -m 'Add some feature'`)
5. Push to branch (`git push origin feature/YourFeature`)
6. Open a Pull Request

## 📧 Contact

**Devteall**  
📧 Email: devteal@gmail.com  
🐦 Twitter: https://x.com/Web3believer?t=rclmaPx4wjGQvz5iq5KiZQ&s=09
💼 LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

**Project Link:** [https://github.com/YOUR_USERNAME/tenant-bill-calculator](https://github.com/YOUR_USERNAME/tenant-bill-calculator)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built to solve real-world tenant billing disputes
- Inspired by the need for fairness and transparency
- Thanks to all roommates who've ever argued about electricity bills 😄

---

### ⭐ Star this repo if you found it helpful!

**Made with ❤️ for tenants everywhere**

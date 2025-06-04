# Windows Gaming Optimization Registry Tweaks

This collection of registry tweaks is designed to optimize your Windows 10/11 system for gaming, particularly for competitive games like Free Fire on BlueStacks. These tweaks focus on improving mouse responsiveness, reducing input lag, and optimizing system performance.

## ⚠️ Important Notes

- **Backup your registry** before applying any changes
- Create a system restore point
- These tweaks are safe and legal for competitive play
- Some changes require a system restart to take effect

## 📁 File Descriptions

| File | Description |
|------|-------------|
| `1_disable_mouse_accel.reg` | Disables mouse acceleration for consistent aiming |
| `2_optimize_priority.reg` | Optimizes process priorities for gaming |
| `3_disable_animations.reg` | Disables visual effects for better performance |
| `4_optimize_network.reg` | Network optimizations for lower ping |
| `5_disable_game_bar.reg` | Disables Windows Game Bar and DVR |
| `6_optimize_power.reg` | Power settings for maximum performance |
| `7_optimize_services.reg` | Disables unnecessary background services |
| `8_optimize_timer.reg` | System timer optimizations |
| `9_optimize_gpu.reg` | GPU performance tweaks |
| `10_ultimate_gaming.reg` | Combines the most important optimizations |
| `11_enhanced_mouse_control.reg` | Advanced mouse precision and control optimizations |
| `mouse_optimization.reg` | Original comprehensive mouse optimization file |

## 🎮 Best Files for Gaming

1. **For general gaming**: `10_ultimate_gaming.reg`
2. **For competitive FPS games**: `11_enhanced_mouse_control.reg`
3. **For low-end PCs**: `3_disable_animations.reg` + `7_optimize_services.reg`
4. **For network-heavy games**: `4_optimize_network.reg`

## 🚀 Quick Start

1. **For best results**, apply all optimizations:
   - Run `10_ultimate_gaming.reg`
   - Then run `11_enhanced_mouse_control.reg`
   - Restart your computer

2. **For specific optimizations**, run individual `.reg` files as needed

## 🔧 How to Apply

1. Double-click the desired `.reg` file
2. Click "Yes" to confirm the User Account Control (UAC) prompt
3. Click "Yes" to confirm the registry modification
4. Restart your computer for all changes to take effect

## 🔄 Reverting Changes

1. Open Registry Editor (Win + R, type `regedit`)
2. Navigate to the modified keys
3. Right-click and select "Delete" to remove the values
4. Or restore your system from the restore point you created

## 🎯 Recommended Settings for Competitive Gaming

1. **Mouse Settings**:
   - DPI: 400-800
   - Polling Rate: 1000Hz (if supported)
   - In-game sensitivity: 1.0 (adjust as needed)
   - Windows pointer speed: 6/11 (no acceleration)

2. **BlueStacks Settings**:
   - CPU: 4 cores
   - RAM: 4GB
   - Performance Mode: High Performance
   - Frame Rate: 60 FPS
   - Graphics Engine: Performance
   - Enable high FPS in game settings

## 🛠️ What's New in v1.1
- Added `11_enhanced_mouse_control.reg` for better precision
- Improved mouse optimization settings
- Better system responsiveness
- Reduced input lag

## 📝 Additional Tips

- Update your graphics drivers regularly
- Close unnecessary background applications
- Use a wired internet connection for lower latency
- Disable Windows Game Mode if you experience issues
- Keep Windows and BlueStacks updated
- For best results, use a gaming mouse with adjustable DPI

## ⚠️ Disclaimer

Use these tweaks at your own risk. Always:
- Create system restore points before making changes
- Follow the game's terms of service
- Use legitimate optimization methods only
- These tweaks do not modify game files or provide unfair advantages

## 🤝 Support

For questions or issues, please open an issue in the repository.

---
*Last Updated: 2025-06-04 | v1.1*

V2Ray Elite - High Performance Xray/V2Ray Client for Android

V2Ray Elite is a sophisticated, open-source VPN client for Android, built upon the robust foundations of v2rayNG. This fork is specifically engineered to bridge the gap between powerful networking capabilities and a modern, user-centric interface.

While maintaining full compatibility with Xray and V2Ray cores, this version focuses on UI/UX optimization, brand identity integration, and workflow efficiency.
💎 Key Enhancements

    Refined UI/UX: A complete departure from the legacy interface, featuring a streamlined dashboard and intuitive navigation.

    Custom Branding: Fully integrated custom iconography and design language.

    Seamless Subscription Management: Optimized handling of remote configurations and server lists.

    Core Versatility: Native support for both Xray-core and v2fly-core.

    Enhanced Routing Control: Simplified management of GeoIP and GeoSite rules for granular traffic steering.

🛠 Technical Overview
Supported Cores

    Xray Core: For cutting-edge XTLS and performance features.

    v2fly Core: For industry-standard V2Ray stability.

System Requirements

    Minimum SDK: API 24 (Android 7.0+)

    Build System: Gradle Wrapper / Android Studio

    Environment: Support for physical devices, Android Emulators, and WSA (Windows Subsystem for Android).

📂 Asset & Rule Management

The application utilizes .dat files for intelligent routing.

    Default Path: Android/data/[PACKAGE_NAME]/files/assets

    Recommended Rulesets: It is highly recommended to use Loyalsoldier/v2ray-rules-dat for enhanced Geo-filtering.

    WSA Note: For Windows Subsystem for Android, grant VPN permissions via ADB:

    appops set [PACKAGE_NAME] ACTIVATE_VPN allow

🏗 Development & Core Compilation

This project can be compiled directly via Android Studio. For developers requiring the absolute latest core binaries (AAR), please refer to:

    AndroidLibXrayLite

    AndroidLibV2rayLite

⚖️ Legal Disclaimer & Licensing

Disclaimer: This software is provided for educational and research purposes only. Users are solely responsible for compliance with local laws and regulations. The developers assume no liability for misuse.

License: This project is licensed under the GPL-3.0 License - maintaining the open-source spirit of the original v2rayNG project.

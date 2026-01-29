# Loja de Cadernos Digitais 📓

A beautiful, modern e-commerce store for digital planners built with **React** and integrated with **WordPress WooCommerce**. This is a complete Figma design-to-code project featuring a professional planner sales platform with a pink and gold aesthetic.

## 🎨 Figma Design

Access the complete design and prototypes on Figma:

👉 **[Figma Design - Loja de Cadernos Digitais](https://www.figma.com/make/Pb4r9oPCe2wME6Yg9LXunk/Loja-de-Cadernos-Digitais?t=ualCz8dXNqbjNdAc-0)**

The Figma file includes:
- Complete UI/UX design for the e-commerce platform
- - All pages and components
  - - Design system and component library
    - - Responsive layouts for desktop and mobile
      - - Detailed prototypes and interactions
        - - AI-generated implementation guides
         
          - ## ✨ Features
         
          - ### Frontend (React)
          - - ✅ Beautiful, responsive design with pink and gold theme
            - - ✅ Product showcase and filtering
              - - ✅ Shopping cart functionality
                - - ✅ Checkout process
                  - - ✅ User authentication
                    - - ✅ Order tracking
                      - - ✅ Digital planner downloads
                        - - ✅ Privacy policy page (LGPD compliant)
                          - - ✅ Affiliate program page
                           
                            - ### Backend (WordPress + WooCommerce)
                            - - ✅ Product management
                              - - ✅ Order processing
                                - - ✅ Payment integration (PIX, Credit Card)
                                  - - ✅ Automatic email notifications
                                    - - ✅ Sales reports and analytics
                                      - - ✅ REST API for frontend communication
                                       
                                        - ### Integration
                                        - - ✅ React frontend connected via WordPress REST API
                                          - - ✅ Automatic product synchronization
                                            - - ✅ Secure API key management
                                              - - ✅ Real-time order updates
                                               
                                                - ## 🚀 Tech Stack
                                               
                                                - - **Frontend**: React, Vite, TypeScript, Tailwind CSS
                                                  - - **Backend**: WordPress, WooCommerce, PHP
                                                    - - **Deployment**: Vercel (Frontend), Traditional hosting (WordPress)
                                                      - - **API**: WordPress REST API
                                                        - - **Design**: Figma
                                                         
                                                          - ## 📦 Project Statistics
                                                         
                                                          - - **4.9/5** Average Rating
                                                            - - **12,500+** Happy Customers
                                                              - - **Professional** E-commerce Solution
                                                               
                                                                - ## 🎯 How It Works
                                                               
                                                                - ```
                                                                  React (Vercel)  ←→ API REST ←→ WordPress (Server)
                                                                     Frontend            |          Backend
                                                                     Beautiful UI        |       Product Data
                                                                     Shopping Cart       |       Order Processing
                                                                     User Experience     |       Payment Handler
                                                                  ```

                                                                  ### User Flow
                                                                  1. User browses products on React frontend
                                                                  2. 2. Products are automatically synced from WordPress
                                                                     3. 3. User adds items to cart and checks out
                                                                        4. 4. Payment processed via WordPress (PIX, Card)
                                                                           5. 5. Digital planner automatically downloaded
                                                                              6. 6. Order confirmation email sent
                                                                                
                                                                                 7. ## 📋 Setup Instructions
                                                                                
                                                                                 8. ### Prerequisites
                                                                                 9. - Node.js (v16+)
                                                                                    - - npm or yarn
                                                                                      - - WordPress installation with WooCommerce
                                                                                        - - Git
                                                                                         
                                                                                          - ### 1. Frontend Setup (React)
                                                                                         
                                                                                          - ```bash
                                                                                            # Clone the repository
                                                                                            git clone https://github.com/yummyrecipes/loja-cadernos-digitais.git
                                                                                            cd loja-cadernos-digitais

                                                                                            # Install dependencies
                                                                                            npm install

                                                                                            # Create environment file
                                                                                            cp .env.example .env

                                                                                            # Configure environment variables
                                                                                            VITE_WORDPRESS_URL=https://your-wordpress.com
                                                                                            VITE_WOOCOMMERCE_KEY=your_consumer_key
                                                                                            VITE_WOOCOMMERCE_SECRET=your_consumer_secret

                                                                                            # Start development server
                                                                                            npm run dev
                                                                                            ```

                                                                                            ### 2. Backend Setup (WordPress)

                                                                                            1. Install WordPress and WooCommerce plugin
                                                                                            2. 2. Add digital planner products to WooCommerce
                                                                                               3. 3. Install WooCommerce REST API authentication
                                                                                                  4. 4. Generate API keys for React frontend:
                                                                                                     5.    - Go to WooCommerce → Settings → Advanced → REST API
                                                                                                           -    - Create new API keys for frontend access
                                                                                                                - 5. Configure API keys in .env file
                                                                                                                 
                                                                                                                  6. ### 3. Deploy
                                                                                                                 
                                                                                                                  7. **Deploy React to Vercel:**
                                                                                                                  8. ```bash
                                                                                                                     npm run build
                                                                                                                     # Push to GitHub and connect with Vercel
                                                                                                                     # Vercel will auto-deploy on push
                                                                                                                     ```
                                                                                                                     
                                                                                                                     **Deploy WordPress:**
                                                                                                                     - Use traditional hosting or WordPress.com
                                                                                                                     - - Ensure REST API is publicly accessible (with authentication)
                                                                                                                      
                                                                                                                       - ## 📖 Documentation
                                                                                                                      
                                                                                                                       - The Figma project includes AI-generated documentation with:
                                                                                                                      
                                                                                                                       - - 📄 **RESUMO-SOLUCAO.md** - Quick overview and summary
                                                                                                                         - - 📄 **GUIA-INTEGRACAO-REACT-WORDPRESS.md** - Step-by-step integration guide
                                                                                                                           - - 📄 **ARQUITETURA-SISTEMA.md** - Technical architecture and diagrams
                                                                                                                            
                                                                                                                             - ## 🔐 Security Notes
                                                                                                                            
                                                                                                                             - ⚠️ **Important Security Requirements:**
                                                                                                                            
                                                                                                                             - 1. **Never commit sensitive data** to the repository:
                                                                                                                               2.    - API keys must be in `.env` file
                                                                                                                                     -    - Ensure `.env` is in `.gitignore`
                                                                                                                                          -    - Use environment variables in production
                                                                                                                                           
                                                                                                                                               - 2. **Production Configuration:**
                                                                                                                                                 3.    - Store API keys in Vercel environment variables (not .env)
                                                                                                                                                       -    - Use HTTPS for all connections
                                                                                                                                                            -    - Implement proper CORS policies
                                                                                                                                                                 -    - Enable WooCommerce security features
                                                                                                                                                                  
                                                                                                                                                                      - 3. **Data Protection:**
                                                                                                                                                                        4.    - LGPD compliant privacy policy
                                                                                                                                                                              -    - Secure payment processing via WooCommerce
                                                                                                                                                                                   -    - Encrypted customer data
                                                                                                                                                                                        -    - Automatic email confirmations
                                                                                                                                                                                         
                                                                                                                                                                                             - ## 💡 Features Breakdown
                                                                                                                                                                                         
                                                                                                                                                                                             - ### Pages
                                                                                                                                                                                             - - **Home** - Marketing homepage with featured products
                                                                                                                                                                                               - - **Shop** - Browse all digital planners with filters
                                                                                                                                                                                                 - - **Product Detail** - Detailed product information and purchase
                                                                                                                                                                                                   - - **Cart** - Shopping cart management
                                                                                                                                                                                                     - - **Checkout** - Secure checkout process
                                                                                                                                                                                                       - - **Account** - User profile and order history
                                                                                                                                                                                                         - - **Privacy Policy** - LGPD compliant privacy information
                                                                                                                                                                                                           - - **Affiliate Program** - Partner opportunities
                                                                                                                                                                                                            
                                                                                                                                                                                                             - ### Components
                                                                                                                                                                                                             - - Navigation bar with search
                                                                                                                                                                                                               - - Product cards and grid
                                                                                                                                                                                                                 - - Filtering and sorting
                                                                                                                                                                                                                   - - Rating system (4.9/5)
                                                                                                                                                                                                                     - - Testimonials section
                                                                                                                                                                                                                       - - Newsletter subscription
                                                                                                                                                                                                                         - - Footer with links
                                                                                                                                                                                                                           - - Mobile responsive layout
                                                                                                                                                                                                                            
                                                                                                                                                                                                                             - ## 📊 Performance
                                                                                                                                                                                                                            
                                                                                                                                                                                                                             - - ⚡ Fast page loads (optimized React bundle)
                                                                                                                                                                                                                               - - 📱 Responsive design for all devices
                                                                                                                                                                                                                                 - - 🔄 Real-time product synchronization
                                                                                                                                                                                                                                   - - 💾 Efficient caching strategies
                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                     - ## 🤝 Contributing
                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                     - We welcome contributions! Please:
                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                     - 1. Fork this repository
                                                                                                                                                                                                                                       2. 2. Create a feature branch (`git checkout -b feature/amazing-feature`)
                                                                                                                                                                                                                                          3. 3. Commit your changes (`git commit -m 'Add amazing feature'`)
                                                                                                                                                                                                                                             4. 4. Push to the branch (`git push origin feature/amazing-feature`)
                                                                                                                                                                                                                                                5. 5. Open a Pull Request
                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                   6. ## 📄 License
                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                   7. This project is licensed under the MIT License - see the LICENSE file for details.
                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                   8. ## 📞 Support
                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                   9. For questions or support:
                                                                                                                                                                                                                                                   10. - 💬 Check the Figma project documentation
                                                                                                                                                                                                                                                       - - 🐛 Open an issue on GitHub
                                                                                                                                                                                                                                                         - - 📧 Contact the team
                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                           - ## 🎉 Project Status
                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                           - **Version**: 1.0
                                                                                                                                                                                                                                                           - **Status**: Active Development
                                                                                                                                                                                                                                                           - **Last Updated**: January 29, 2026
                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                           - ## 🙏 Credits
                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                           - Created as a demonstration of modern e-commerce development combining:
                                                                                                                                                                                                                                                           - - Professional Figma design system
                                                                                                                                                                                                                                                             - - React frontend development
                                                                                                                                                                                                                                                               - - WordPress backend integration
                                                                                                                                                                                                                                                                 - - Modern deployment practices
                                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                                   - ---
                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                   **Ready to sell digital planners? Start here! 🚀💰**
                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                   Visit the [Figma Design](https://www.figma.com/make/Pb4r9oPCe2wME6Yg9LXunk/Loja-de-Cadernos-Digitais?t=ualCz8dXNqbjNdAc-0) to see the complete vision for this project.

# Basics

  Key Of Developemnt
  
        - Oops
        
        - Debug
           - RCA
           - Quick Fixes
           - Reading Logs
        
        - Error Handling
                - Fallback
                - Friendly messages to users
                - Handling Timeouts
                - Handling Network Failure
                - Handling Deadlocks
                - Centralized Error Handler
                - Prevent Silent Failures
        
        - Logger
            - Structured Logging (JSON format recommended)
            - DEBUG, INFO, WARN, ERROR, CRITICAL
            
        - Avoid Deprecate
             - Functions
             - Libraries
             - APIs
             - Classes
             - Methods
             
        - Coding standard (Technology Wise) - SOLID , DRY , KISS, Design Patterns
               - Modularity
               - Reusability
               - Avoid hardcoded values
               - Environment variables usage
               - Proper code indentation
               - Consistent naming conventions
               - Folder structure standards
               - Avoid deeply nested loops
               - Code comments only where necessary
               - Documentation / Docstrings

       - Testing
            - Unit Testing
            - Integration Testing
            - API Testing
            - End-to-End Testing
            - Regression Testing
            - Load Testing
            - Smoke Testing
            - Security Testing
            - A/B Testing for product-level validation
            

### Concept Of Software Development (no matter what language )
##### Application Flow

       user(frontend flow)
       -------------------
           - home page 
           - products (types of product)
                        |
                        |-- Simple
                        |-- Configurable
                        |-- Grouped
                        |-- Bundle
                        |-- Virtual
                        |-- Bundle 
           - plp page
           - pdp page
           - add to cart | add to wishlist
           - cart rules (apply coupon | gift cards)
                    |----- catalog ruels
                    |----- cart rules
                    |----- tier price 
           - procced to checkout
           - add biling address | add shipping address
           - add card details
           - place order 
                    |----- new
                    |----- processing
                    |----- complete
                    |----- invoice
                    |----- shipment
                    |----- deliver
                    |----- return (RMA -- create retun, approve retunr , ex-change item, get money back )
                    |----- credit memo
                    

       backend flow(table flow)
       ------------------------

##### BackBone

      - Time Complexity:
           - O(1), O(log n), O(n), O(n log n), O(n²)
      - Space Complexity
      - Performance Optimization
            - Algorithmic Optimization
            - Query Optimization
            - API Optimization
            - Memory Optimization
         
##### Setup Tools
     why need
            - nginx
            - php / java / python
            - npm / yarn
            - Composer / Maven / Gradle
            - apache
            - tomcat
            - ElasticSearch / OpenSearch
            - Redis
            - RabbitMQ / Kafka
            - Varnish
##### Frontend 
          - RWD 
          - Skeleton - preloaded
          - Lazy Loading
          - Image Optimization
          - Web Workers
          - Component Architecture
          

##### PWA 

      - Service Workers
      - Add to Home Screen
      - Offline Mode
      - Push Notifications
      - Background Sync
      - App Manifest
      
##### API
        - REST APIS (Swaggr / Postman) 
        - GraphQl (GraphQl Altair)
        - Response Status Codes
             
##### Backend
     - Business Logic Layer
     - Authentication & Authorization
     - OAuth / JWT
     - Session Handling
     - Caching
     - Event-driven architecture
     - Microservices
     - Serverless Functions
     - Data Validation
     - File Uploads
     - Error Logging
     - Sentry / ELK / Loki
          
##### Database 
        - relational
               - Mysql
               - PostgreSQL
               - MariaDB

        - non-relational
                - MongoDb
                - DynamoDB
                - CouchDB
                - Redis (Key-Value)

    - Best Practices
           - Normalize when needed
           - Denormalize when scaling
           - Proper indexing
           - Optimized JOINs
           - ACID compliance
           - Avoid full-table scans
           - Use transactions effectively
           - Caching frequently-used queries
           - Sharding / Replication for scaling
           
               
##### Security 
         - OWASP Top 10
         - SQL Injection
         - XSS
         - SSRF
         - CSRF
         - Rate Limiting
         - Token Expiration
         - Encryption: AES, RSA
         - HTTPS/SSL
         - CORS
         - Security Testing Tools
            - Burp Suite
            - Nessus
            - nmap


##### B2B 
       - newrelic
       - shared catalog 
       - tier pricing 
       - Shared Catalog
       - Customer Groups


##### Hoisting and Cloud
         |
         |----- AWS 
         |
         |----- Azure
         |
         |----- GCP 

##### Third-Party

        - Klevu 
        - ERP
        - 

##### Functionality 

      - Login | Register 
                  |
                  |---- apple login
                  |---- google login
                  |---- any social media 

      - Payment
           |
           |---- Tabby | PostPay
           |---- Adyen (Apple Pay | Google Pay ) 
           |---- PayPal
           |---- Tabby | Postpay
           |---- Credit Cards 


##### SEO and Marketing (If Google Closed - what is the alternative)

    - user came to site and where they left
        
         - Google Tag Manager 
         
         - Google Analytics (GA4)

         - Facebook Pixel
         
         - Tredning Apps Country wise (from where customer is visting to website)
                           |
                           |--- tiktok 
                           |--- linkedin 
    


##### Tools & Technology

       - Git , Github , Gitlab
       - Docker , Jenkins , Ansible , 
       - RabbitMq / Sonar Cube
       - Cron Job
       - WSL / Hyper-V
       - Xdebuger
       - 
          

#### Performance & Optimization
     - Identify bottlenecks
     - Reduce DB calls
     - Use caching strategically
     - Use pagination, not full dataset loads
     - Optimize loops
     - Reduce network requests
     - Query Optimization
     - Indexing
     - CDN usage for static content
     - Lazy loading
     - Profiling tools
     - Memory leak detection
             
 

   




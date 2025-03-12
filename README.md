init:
	cd backend_order_food_and_drink/ && npm i
	cd frontend_order_food_and_drink/ && npm i

run-server:
	cd backend_order_food_and_drink/ && npm start && cd ..

# Database
kết nối database MongoDB thông qua Mongoose.(MongoDB + Mongoose)

# cấu trúc thư mục
backend_order_food_and_drink
│── .vscode/              
│── app/                  
│   │── config/             
│   │── controllers/       
│   │── helpers/          
│   │── models/             
│   │── routes/             
│   │── socket/            
│   │── test/              
│── static/                
│── variables/              
│── .env                    
│── .gitignore              
│── package.json            
│── server.js               
│── README.md

# Hướng dẫn chạy
cd đường dẫn thư mục\food_and_drink4\order_food_and_drink\order_food_and_drink\order_food_and_drink\frontend_order_food_and_drink
->npm run dev 
-frontend chạy bằng quyền admin

# Cấu trúc thư mục
frontend_order_food/
│── public/                   
│
│── src/                      
│   ├── api/                  
│   ├── assets/               
│   ├── components/           
│   ├── hooks/                
│   ├── layouts/              
│   ├── pages/                
│   ├── redux/                
│   │   ├── slices/           
│   │   ├── store.js          
│   ├── routes/               
│   ├── styles/               
│   ├── utils/                
│   ├── App.js                
│   ├── index.js              
│
│── .env                      
│── .gitignore                
│── package.json              
│── README.md                 

# **BookeState Room Reservation Website**  

## **Project Overview**  
BookeState is a full-stack room and hotel reservation system that connects users with accommodations tailored to their preferences. The platform allows users to search by location, view detailed room profiles, and register as vendors to list their own accommodations.  


## **Key Features**  
### **User Features**  
- **Search and Filter**: Find accommodations by location and preferences.  
- **Detailed Room Profiles**: Access information like amenities, pricing, and location.  
- **Secure Authentication**: User registration and login system.  

### **Vendor Features**  
- **Vendor Enrollment**: Switch to a vendor profile to list accommodations.  
- **Room Management**: Add and manage room details.  


## **Technologies Used**  
- **Frontend**: React, TailwindCSS  
- **Backend**: Express.js, Node.js  
- **Database**: MongoDB  
- **Image Storage**: Cloudinary  
- **Deployment**: Render  


## **How to Run Locally**  
### **Prerequisites**  
1. Node.js and npm installed.  
2. MongoDB installed or access to a cloud MongoDB instance.  

### **Steps**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/bookestate-room-reservation.git  
   cd bookestate-room-reservation  
   ```  
2. Install dependencies:  
   ```bash  
   npm install  
   ```  
3. Set up `.env` file with required environment variables:  
   ```plaintext  
   MONGO_URI=your-mongodb-uri  
   ```  
4. Start the development server:  
   ```bash  
   npm run dev  
   ```  
5. Visit the app at `http://localhost:3000`.  


## **Future Enhancements**  
- **AI Search Recommendations**: Tailored search results based on user behavior.  
- **Dynamic Pricing**: Automated pricing adjustments based on demand.  
- **Personalized Suggestions**: Recommend accommodations based on previous bookings.  

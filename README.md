# Kiểm thử API với Postman

## Giới thiệu
Mục tiêu của bài tập này là thực hành kiểm thử API bằng cách sử dụng Postman. Bài tập bao gồm các bước từ việc lựa chọn một API thực tế, phân tích tài liệu API, viết các trường hợp kiểm thử, thực hiện kiểm thử và ghi lại kết quả kiểm thử.

## API Được Chọn
API được lựa chọn cho bài tập này là **OpenWeatherMap API**, một API phổ biến cung cấp dữ liệu thời tiết theo thời gian thực.
## Kết Quả Kiểm Thử

### Trường Hợp Kiểm Thử 1
![anh1](https://github.com/chungtringuyen/kiemthu/blob/166b622baceba73dbae73b71854bd6b31a74c5b9/Screenshot%202024-05-24%20174953.png)
"id": 4123,
    "uid": "fee3cee0-f2bc-4fef-af69-fd15ef0447dc",
    "password": "3jBNswWJO7",
    "first_name": "Earle",
    "last_name": "Kohler",
    "username": "earle.kohler",
    "email": "earle.kohler@email.com",
    "avatar": "https://robohash.org/etremcorrupti.png?size=300x300&set=set1",
    "gender": "Genderqueer",
    "phone_number": "+247 (491) 767-3080 x38127",
    "social_insurance_number": "225557958",
    "date_of_birth": "2000-03-18",
    "employment": {
        "title": "Customer Engineer",
        "key_skill": "Technical savvy"

--Kiểm thử không lỗi
### Trường Hợp Kiểm Thử 2
![anh2](https://github.com/chungtringuyen/kiemthu/blob/166b622baceba73dbae73b71854bd6b31a74c5b9/Screenshot%202024-05-24%20180327.png)
- api trả về status 200 tức trạng thái ok tức là không lỗi
- phương thức sử dụng : GET 
- api trả về Response:
- "id": 4123,
    "uid": "fee3cee0-f2bc-4fef-af69-fd15ef0447dc",
    "password": "3jBNswWJO7",
    "first_name": "Earle",
    "last_name": "Kohler",
    "username": "earle.kohler",
    "email": "earle.kohler@email.com",
    "avatar": "https://robohash.org/etremcorrupti.png?size=300x300&set=set1",
    "gender": "Genderqueer",


SOURCE OF CODE:

    def cal_ave_rat(quality, price, service):
        return (quality + price + service) / 3.0
    
    def anal_pro_rat(product_name, category, quality, price, service):
        print("\nProduct Name:", product_name)
        print("Category:", category)
        print(f"Quality Rating: {quality:.2f}")
        print(f"Price Rating: {price:.2f}")
        print(f"Service Rating: {service:.2f}")
        overall = cal_ave_rat(quality, price, service)
        print(f"Overall Average Rating: {overall:.2f}")
    
    name = input("Enter Product Name: ")
    category = input("Enter Category: ")
    quality = float(input("Enter Quality Rating: "))
    product = float(input("Enter Price Rating: "))
    service = float(input("Enter Service Rating: "))
    
    anal_pro_rat(name, category, quality, product, service)

OUTPUT:
<img width="286" height="289" alt="image" src="https://github.com/user-attachments/assets/f60826ab-c35a-4ab5-b09e-a0d35e00cbe7" />

    

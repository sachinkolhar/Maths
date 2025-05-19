#  chain rule.
![WhatsApp Image 2025-05-19 at 17 23 44_e878584a](https://github.com/user-attachments/assets/dc25bb86-7cb1-4bc3-b7b9-c9d4aedbf47f)

**1. Basic Chain Rule with One Intermediate Variable**

* **z = f(x, y), x = g(t), y = h(t)**

   If z is a function of x and y, and x and y are functions of a single variable t, then:

   ```
   dz/dt = (∂z/∂x) * (dx/dt) + (∂z/∂y) * (dy/dt)
   ```

**2. Chain Rule with Multiple Intermediate Variables**

* **z = f(x, y), x = g(s, t), y = h(s, t)**

   If z is a function of x and y, and x and y are functions of two variables s and t, then:

   ```
   ∂z/∂s = (∂z/∂x) * (∂x/∂s) + (∂z/∂y) * (∂y/∂s)
   ∂z/∂t = (∂z/∂x) * (∂x/∂t) + (∂z/∂y) * (∂y/∂t)
   ```

**3. Generalization to More Variables**

* **w = f(x, y, z), x = g(t), y = h(t), z = k(t)**

   If w is a function of x, y, and z, and x, y, and z are functions of a single variable t, then:

   ```
   dw/dt = (∂w/∂x) * (dx/dt) + (∂w/∂y) * (dy/dt) + (∂w/∂z) * (dz/dt)
   ```

* **w = f(x, y, z), x = g(s, t), y = h(s, t), z = k(s, t)**

   If w is a function of x, y, and z, and x, y, and z are functions of two variables s and t, then:

   ```
   ∂w/∂s = (∂w/∂x) * (∂x/∂s) + (∂w/∂y) * (∂y/∂s) + (∂w/∂z) * (∂z/∂s)
   ∂w/∂t = (∂w/∂x) * (∂x/∂t) + (∂w/∂y) * (∂y/∂t) + (∂w/∂z) * (∂z/∂t)
   ```

**4. Implicit Differentiation**

* **F(x, y, z) = 0**

   If z is defined implicitly as a function of x and y by the equation F(x, y, z) = 0, then:

   ```
   ∂z/∂x = - (∂F/∂x) / (∂F/∂z)
   ∂z/∂y = - (∂F/∂y) / (∂F/∂z)
   ```

**Example: Tree Diagram**

For z = f(x, y), x = g(s, t), y = h(s, t), the tree diagram would look like this:

```
        z
       / \
      x   y
     / \ / \
    s  t s  t
```

This visually represents how z depends on x and y, and x and y depend on s and t.

------------------------------

# 1) Find the critical point(s) of the following functions and determine the nature of each using the Hessian.
<img width="386" alt="image" src="https://github.com/user-attachments/assets/4d0686da-83aa-497e-b33d-2ea3f3e92521" />

-----
# Jacobian
<img width="646" alt="image" src="https://github.com/user-attachments/assets/c7d9becd-3339-4da7-a7d5-ff86a132b4d6" />
<img width="685" alt="image" src="https://github.com/user-attachments/assets/2dba865e-dc38-49cf-8718-828d306c761e" />

---------------------
# Linearization 
<img width="634" alt="image" src="https://github.com/user-attachments/assets/ad9d65f5-4117-4432-ae6e-5b8d1b55b878" />

------------------
# Optimization Using Gradient Descent
![WhatsApp Image 2025-05-18 at 21 09 53_12e24d83](https://github.com/user-attachments/assets/7f0b059e-3ddf-4988-b180-b7376824871c)

----------------------------
# Tangent Plane Equation:

<img width="392" alt="image" src="https://github.com/user-attachments/assets/00c8629d-1899-4cab-b9ed-3f84deb27c29" />
<img width="443" alt="image" src="https://github.com/user-attachments/assets/ad860645-f877-4928-909a-f601adee91c7" />
<img width="523" alt="image" src="https://github.com/user-attachments/assets/30e50faa-826c-4a4e-ab93-d0a7913a338b" />
<img width="534" alt="image" src="https://github.com/user-attachments/assets/9ef8e7d0-fef8-4f90-8f55-42127f0dea27" />

--------------------------
# del operator
<img width="272" alt="image" src="https://github.com/user-attachments/assets/856879c7-98c3-49b5-bb17-f9b5c1696d31" />
<img width="434" alt="image" src="https://github.com/user-attachments/assets/b6c4ec31-d31d-4cc3-bc81-bdd4f75d9e0f" /> <br>
<img width="389" alt="image" src="https://github.com/user-attachments/assets/5aa55ced-b6d3-44ab-92a7-ffd70c6ab25c" />
<img width="154" alt="image" src="https://github.com/user-attachments/assets/25717bee-f0d2-42eb-95dc-36894dbad208" />
<img width="514" alt="image" src="https://github.com/user-attachments/assets/314ff473-c25e-4971-84f4-e943f56f848d" /> <br>
<img width="569" alt="image" src="https://github.com/user-attachments/assets/81353931-b360-4f51-9ab4-ac215c67b582" />

------------
## directional derivative <br>
<img width="511" alt="image" src="https://github.com/user-attachments/assets/cf338043-2dee-4a3a-a11b-a88a943e096e" />
<img width="806" alt="image" src="https://github.com/user-attachments/assets/b257cbc5-7718-4242-8618-fe1bdbc3a064" />

## two different F <br>
<img width="272" alt="image" src="https://github.com/user-attachments/assets/02ee9a1e-b49d-4222-9456-783ac06e8afb" /> <br>
<img width="821" alt="image" src="https://github.com/user-attachments/assets/b4a6eacc-b0a7-422e-b8b9-3955451bc5af" />
<img width="492" alt="image" src="https://github.com/user-attachments/assets/905e0cc1-a121-4ff7-b11c-6235be7a28f4" />

------------------------------
# Multivariable Taylor series
## f(x)
<img width="433" alt="image" src="https://github.com/user-attachments/assets/5ee25ab9-2cef-40c0-9f64-39bc1b64f444" /> <br>

## f(x,y)
![WhatsApp Image 2025-05-19 at 14 21 08_ab3969e9](https://github.com/user-attachments/assets/7a182b1f-14fe-4e23-89ff-466b81c0afe8) <br>
<img width="466" alt="image" src="https://github.com/user-attachments/assets/ee9f97c4-8d2f-4544-9e12-a1503601f97f" /> <br>

<img width="686" alt="image" src="https://github.com/user-attachments/assets/e9e17722-ab00-4d94-89d0-2085a1f789bf" /> <br>
1. Single-variable Taylor series <br>
<img width="680" alt="image" src="https://github.com/user-attachments/assets/c9782507-997c-4852-9588-99918b68c348" /> <br>
2. Multivariable Taylor series (2 variables) <br>
<img width="535" alt="image" src="https://github.com/user-attachments/assets/b32f9adf-adce-4108-849e-6d36a3b4412e" /> <br>

The multivariate Taylor series provides a local approximation of a function using derivatives. The key takeaways are:

The first-order term is based on the gradient.

The second-order term is based on the Hessian matrix.

Higher-order terms involve tensor derivatives.

<img width="787" alt="image" src="https://github.com/user-attachments/assets/cdc1dc91-26db-45fc-a8b1-1f7246830f32" />
<img width="647" alt="image" src="https://github.com/user-attachments/assets/3f5f9437-1a2d-4207-8281-42d3ff30d2a1" />
<img width="776" alt="image" src="https://github.com/user-attachments/assets/394ebc93-159b-414f-8db3-5fac8eea29ba" />

---------------
<img width="815" alt="image" src="https://github.com/user-attachments/assets/b68ae1bf-40c4-46af-8d3d-f093f6105d9c" />
<img width="652" alt="image" src="https://github.com/user-attachments/assets/8f4499d5-e01d-4983-9582-1029568940cf" />
<img width="476" alt="image" src="https://github.com/user-attachments/assets/b01b2771-4228-4e46-8c04-36ffc7862755" />


![WhatsApp Image 2025-03-24 at 18 12 17_24650682](https://github.com/user-attachments/assets/5ffab0c3-86a3-4ed3-ac21-e5e52136941b)

-----

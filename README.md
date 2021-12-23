# GF-Product-Card

Este es un paquete de pruebas de despliegue de NPM

### German Ferreyra

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'gf-product-card';
```

```
<ProductCard 
        product={product}
        initialValues = {{
            count:4,
            // maxCount:10
        }}
                       
>
        {
            ({ reset, increaseBy, count, isMaxCountReached })=> (
                <>
                    <ProductImage />
                    <ProductTitle />
                    <ProductButtons />
                </>
            )
        }
                        
</ProductCard>
```
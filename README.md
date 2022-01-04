# EJBL-product-card-yiye

Este es un paquete de pruebas de despliegue en NPM

### Eduardo Berzunza

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'ejbl-product-card-yiye'

```

```
 <ProductCard
  product={product}
  initialValues={{
    count: 4,
    maxCount: 10,
  }}
>
  {({ reset, increaseBy, count, isMaxCountReached }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```

# NestJS Core va Dependency Injection Test

## 1. NestJS'da `@Module()` dekoratoriga berilgan obyektdagi `providers` nima uchun ishlatiladi?

C) DI Container'da serviceni ro'yxatdan o'tkazish uchun  

## 2. NestJS'da quyidagi provider turlaridan qaysi biri mavjud emas?
  
C) useConstructor  

## 3. NestJS'da circular dependency (doiraviy bog'liqlik) muammosini hal qilish uchun qaysi mexanizmdan foydalaniladi?

B) forwardRef() funksiyasi  

## 4. `@Injectable()` dekoratori NestJS'da nimani anglatadi?

A) Bu class DI container orqali inject qilinishi mumkin  

## 5. NestJS'da provider'lar qanday scopelarda ishlashi mumkin?

B) DEFAULT, REQUEST, TRANSIENT  

## 6. NestJS'da modulni global qilish uchun qaysi dekoratordan foydalaniladi?

C) @Global()  

## 7. NestJS'da dynamic modul yaratishda qaysi interface ishlatiladi?

B) DynamicModule  

## 8. NestJS'dagi `exports` arrayining vazifasi nima?

B) Provider'larni boshqa modullarga eksport qilish  

## 9. NestJS'da provider'ni custom token bilan ro'yxatdan o'tkazish uchun qaysi sintaksisdan foydalaniladi?

C) `{ provide: 'CONFIG', useClass: ConfigService }`  

## 10. Factory provider NestJS'da qanday ishlatiladi?

A) `{ provide: Service, useFactory: () => new Service() }`  

## 11. NestJS'da constructor injection'da service'larni qanday ko'rsatasiz?
 
B) `constructor(private readonly service: Service) {}`  

## 12. NestJS'da modullar o'rtasida circular dependency'ni qanday yechish mumkin?
 
C) `@Module({ imports: [forwardRef(() => ModuleB)] })`  

## 13. NestJS'da DI container nima uchun javobgar?  
 
C) Provider'larning instance'larini yaratish va inject qilish uchun  

## 14. NestJS'da property injection qanday amalga oshiriladi?
  
B) `@Inject() service: Service`  

## 15. NestJS'da multi-provide qanday ishlaydi?     

A) Bir nechta providerlarni bitta token bilan yaratish  

## 16. Custom provider token sifatida qanday tipdan foydalanish mumkin?
 
C) String, Symbol yoki class  

## 17. `ModuleRef` NestJS'da nima uchun ishlatiladi?    
 
D) Provider'larning instance'lariga runtime'da kirish uchun     

## 18. NestJS'dagi modullar qaysi architectural patternni qo'llaydi?    

C) Modulli arxitektura va Dependency Injection  

## 19. NestJS'da provider'ni o'zgartirish (override) uchun qaysi metoddan foydalaniladi?    
 
B) `.overrideProvider()`     

## 20. NestJS `useExisting` provider tipining vazifasi nimada?

A) Mavjud provider uchun alias yaratish  

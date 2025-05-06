# NestJS Core va Dependency Injection Test

## 1. NestJS'da `@Module()` dekoratoriga berilgan obyektdagi `providers` nima uchun ishlatiladi?

C) DI Container'da serviceni ro'yxatdan o'tkazish uchun  

## 2. NestJS'da quyidagi provider turlaridan qaysi biri mavjud emas?
  
C) useConstructor  

## 3. NestJS'da circular dependency (doiraviy bog'liqlik) muammosini hal qilish uchun qaysi mexanizmdan foydalaniladi?

A) @InjectAll() dekoratori  
B) forwardRef() funksiyasi  
C) CircularResolver utility  
D) @Self() dekoratori

## 4. `@Injectable()` dekoratori NestJS'da nimani anglatadi?

A) Bu class DI container orqali inject qilinishi mumkin  
B) Bu class HTTP so'rovlarni qabul qilishi mumkin  
C) Bu class faqat bir marta yaratiladi  
D) Bu class middleware sifatida ishlaydi

## 5. NestJS'da provider'lar qanday scopelarda ishlashi mumkin?

A) DEFAULT, GLOBAL, LOCAL  
B) DEFAULT, REQUEST, TRANSIENT  
C) SINGLETON, INSTANCE, TEMPORARY  
D) GLOBAL, LOCAL, TEMPORARY

## 6. NestJS'da modulni global qilish uchun qaysi dekoratordan foydalaniladi?

A) @GlobalModule()  
B) @Public()  
C) @Global()  
D) @Scope(Scope.GLOBAL)

## 7. NestJS'da dynamic modul yaratishda qaysi interface ishlatiladi?

A) ModuleFactory  
B) DynamicModule  
C) CustomModule  
D) ConfigurableModule

## 8. NestJS'dagi `exports` arrayining vazifasi nima?

A) Controller'larni eksport qilish  
B) Provider'larni boshqa modullarga eksport qilish  
C) Middleware'larni eksport qilish  
D) DTO'larni eksport qilish

## 9. NestJS'da provider'ni custom token bilan ro'yxatdan o'tkazish uchun qaysi sintaksisdan foydalaniladi?

A) `{ token: 'CONFIG', provider: ConfigService }`  
B) `{ name: 'CONFIG', useClass: ConfigService }`  
C) `{ provide: 'CONFIG', useClass: ConfigService }`  
D) `{ inject: 'CONFIG', target: ConfigService }`

## 10. Factory provider NestJS'da qanday ishlatiladi?

A) `{ provide: Service, useFactory: () => new Service() }`  
B) `{ factory: () => new Service() }`  
C) `@Factory(() => new Service())`  
D) `{ useClass: ServiceFactory }`

## 11. NestJS'da constructor injection'da service'larni qanday ko'rsatasiz?

A) `constructor(@Inject() private service: Service) {}`  
B) `constructor(private readonly service: Service) {}`  
C) `constructor(@Service() private service) {}`  
D) `constructor(@Injectable(Service) private service) {}`

## 12. NestJS'da modullar o'rtasida circular dependency'ni qanday yechish mumkin?

A) `@Module({ imports: [circular(ModuleB)] })`  
B) `@Module({ imports: [async() => ModuleB] })`  
C) `@Module({ imports: [forwardRef(() => ModuleB)] })`  
D) `@Module({ lazyImports: [ModuleB] })`

## 13. NestJS'da DI container nima uchun javobgar?

A) Controllerlarda HTTP so'rovlarni marshallashtirish uchun  
B) Middleware'larni pipeline'ga qo'shish uchun  
C) Provider'larning instance'larini yaratish va inject qilish uchun  
D) Modullar o'rtasida ma'lumot almashish uchun

## 14. NestJS'da property injection qanday amalga oshiriladi?

A) `@InjectProperty() service: Service`  
B) `@Inject() service: Service`  
C) `service: Service = inject(Service)`  
D) `@Autowire() service: Service`

## 15. NestJS'da multi-provide qanday ishlaydi?

A) Bir nechta providerlarni bitta token bilan yaratish  
B) Provider ustiga provider yozish (@Override pattern)  
C) Bir nechta modullarni birlashtirish  
D) Bitta provider'dan bir nechta nusxa yaratish

## 16. Custom provider token sifatida qanday tipdan foydalanish mumkin?

A) Faqat string  
B) Faqat class  
C) String, Symbol yoki class  
D) Faqat Symbol

## 17. `ModuleRef` NestJS'da nima uchun ishlatiladi?

A) Modulni o'zgartirish uchun  
B) Modulni dinamik tarzda yaratish uchun  
C) Modulni runtime'da import qilish uchun  
D) Provider'larning instance'lariga runtime'da kirish uchun

## 18. NestJS'dagi modullar qaysi architectural patternni qo'llaydi?

A) MVC (Model-View-Controller)  
B) MVVM (Model-View-ViewModel)  
C) Modulli arxitektura va Dependency Injection  
D) Active Record

## 19. NestJS'da provider'ni o'zgartirish (override) uchun qaysi metoddan foydalaniladi?

A) `@Override()`  
B) `.overrideProvider()`  
C) `@Replace()`  
D) `.useInsteadOf()`

## 20. NestJS `useExisting` provider tipining vazifasi nimada?

A) Mavjud provider uchun alias yaratish  
B) Mavjud instanceni yangilash  
C) Yangi instance yaratish  
D) Contextga yangi provider qo'shish

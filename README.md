
<!---
jayybluntzzz/jayybluntzzz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview li

@class StockTiker;

@protocol UIStockTickerDelegate<NSObject>

@required
- (NSInteger)numberOfRowsintickerView:(StockTiker *)tickerView;
- (id)tickerView:(StockTiker*)tickerView cellForRowAtIndex:(int)index;
@end

@interface StockTiker : UIScrollView<UITableViewDataSource>
{
    @private
    int count;
    int numberOfObjects;
    id<UIStockTickerDelegate> tdelegate;
}

@property (assign) id<UIStockTickerDelegate>tdelegate;
@property(assign)NSUInteger ttag;

-(void)start;
@endnk to take a look at your changes.
--->

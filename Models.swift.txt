import Foundation

struct Product: Identifiable {
    let id = UUID()
    var name: String
    var cost: Int
    var price: Int
    var stock: Int
    var profit: Int { price - cost }
}

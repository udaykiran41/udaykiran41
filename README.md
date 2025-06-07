class HomeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Welcome to Flipkart')),
      body: Center(
        child: Text('Product Listing Screen Here', style: TextStyle(fontSize: 18)),
      ),
    );
  }
}

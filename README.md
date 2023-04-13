# Altijd-halal-supermarkt-
// Importeer de nodige componenten en API's
import com.google.android.material.bottomnavigation.BottomNavigationView;
import androidx.navigation.NavController;
import androidx.navigation.Navigation;
import androidx.navigation.ui.AppBarConfiguration;
import androidx.navigation.ui.NavigationUI;

// Definieer de MainActivity-klasse
public class MainActivity extends AppCompatActivity {

    // Definieer de nodige variabelen en componenten
    private BottomNavigationView bottomNavView;
    private NavController navController;
    private AppBarConfiguration appBarConfiguration;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Initialiseer de bottomNavView en navController
        bottomNavView = findViewById(R.id.bottomNavigationView);
        navController = Navigation.findNavController(this
// Importeer de nodige componenten en API's
import com.google.android.material.bottomnavigation.BottomNavigationView;
import androidx.navigation.NavController;
import androidx.navigation.Navigation;
import androidx.navigation.ui.AppBarConfiguration;
import androidx.navigation.ui.NavigationUI;

// Definieer de MainActivity-klasse
public class MainActivity extends AppCompatActivity {

    // Definieer de nodige variabelen en componenten
    private BottomNavigationView bottomNavView;
    private NavController navController;
    private AppBarConfiguration appBarConfiguration;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Initialiseer de bottomNavView en navController
        bottomNavView = findViewById(R.id.bottomNavigationView);
        navController = Navigation.findNavController(this

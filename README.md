This is a README.


# headline 2

t2

    type Props = {
      title?: string;
      count?: number;
      onClick: () => void;
    };
    
    function NodeHeader({ title = "Untitled", count = 0, onClick }: Props) {
      // ...
    }

